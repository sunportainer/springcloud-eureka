# springcloud-eureka
查看项目中的PDF文档，了解项目的历史和演示目的
In this example we are going to use Eureka Server as the service registry. Eureka is developed by Netflix; it is open source. Spring has integrated Eureka into dedicated Spring Cloud modules to make it easier to use it.
We are going to develop two microservices:
First is 'hello-service' which will just return a hello message.
Second service 'hello-web-client-service' will handle the request coming from a client. On receiving a request it will call 'hello-service' and will return a web page in response.

There will be three separate servers; one for Eureka and two of microservices. Also there will be three separate maven projects.
