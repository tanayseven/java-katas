test: ./bin/False.class
	! java -cp ./bin False 

./bin/False.class: ./src/False.java
	javac -d ./bin ./src/False.java

clean:
	rm -rf bin/*
