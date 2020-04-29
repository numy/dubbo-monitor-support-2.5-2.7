
针对dubbo2.7及以下版本【含2.8.4 from DangDang】服务的监控

因为阿里只提供了对dubbo2.6.0版本服务的dubbo-monitor监控, 故在此之上进行了部分修改, 能同时支持多版本duboo的接口。

支持同时监控多个注册中心




原作者: Ares

原作者邮箱: xuebing3@asiainfo.com

numy@163.com

How to install this dubbo-monitor:
  1)  cd $proj_home\dubbo-monitor-support-2.5-2.7,execute follow maven command:
    mvn -Dmaven.test.skip=true clean package

  2) get target file
      $proj_home\dubbo-monitor-support-2.5-2.7\target\dubbo-monitor-simple-2.7.3-assembly.tar.gz
      
  3) unzip or untar the file
  
  4) edit dubbo.properties in the unzip File as you want
  
  5) execute assembly.bin/start.sh to start
  
  6) visit 127.0.0.1:8087[same with dubbo.properties specify]
       
