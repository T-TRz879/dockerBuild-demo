# 镜像来源
FROM liferay/jdk11-jdk8
# 将jar包移动到app.jar
ADD dockerBuild-demo-1.0-SNAPSHOT.jar app.jar
# 启动jar包
ENTRYPOINT ["java","-jar","/app.jar"]
# 暴露端口
EXPOSE 7788