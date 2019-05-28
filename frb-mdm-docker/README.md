mvn clean install

docker build -t {image-name} .

	example: docker build -t greeting-app .
	
docker run -d -p 4000:4000 greeting-app	
	

