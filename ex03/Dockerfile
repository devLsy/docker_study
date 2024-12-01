#Dockerfile
FROM nginx

#docker build 실행 경로: C:\Users\사용자명\DOCKER_LAB\ex03
#이 경로 하단에 webapp폴더, conf폴더 
COPY webapp /usr/share/nginx/html
COPY conf/nginx.conf /etc/nginx/conf.d/default.conf
    
ENTRYPOINT [ "nginx", "-g", "daemon off;"]

#Dockerfile로 이미지 만들 때 nginx index html파일과 .conf 설정 파일 복사 해서 
#내가 설정한 html파일이 제대로 표시되는지 확인하는 테스트
#index.html, 40x.html이 제대로 표시되는지 확인