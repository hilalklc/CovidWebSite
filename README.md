# DockerFile CovidWebSite

Creating a website using React that displays the current global COVID situation

## Installation

first of all you need to download docker.you can google it.
after that you should install this project to local   

```bash
git clone https://github.com/hilalklc/CovidWebSite
```

## Usage
you must build this project with docker  
```bash
docker image build -t <imagetag> .
```
<imagetag> : Write which tag you want to give

after that you can run with this command 


```bash
docker run -i -p <port>:3000 <imagetag>
```
this project work with 3000 port so 
##
<port> : Write which port your computer wants to connect to container 3000 port


# testing

You can test it by sending a request to this url, as a result, it will return you instant time.
http://localhost:<5000>/api/get

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
