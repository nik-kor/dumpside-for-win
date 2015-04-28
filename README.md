# dumpside-for-win


node.bat

start java -jar selenium-server-standalone-2_45_0.jar -role node -hub http://localhost:4444/grid/register^
 -Dwebdriver.chrome.driver=.\drivers\chromedriver.exe -Dwebdriver.ie.driver=.\drivers\IEDriverServer.exe
 
hub.bat

start java -jar selenium-server-standalone-2_45_0.jar -role hub
