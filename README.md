tomcat-users.xml
<role rolename="manager-script"/>

<user username="jenkins"
      password="jenkins123"
      roles="manager-script"/>
context.xml
<Valve className="org.apache.catalina.valves.RemoteCIDRValve"
       allow="127.0.0.0/8,::1/128" />
bin
startup.bat
