# Docker-Container

```
가상환경을 사용하는 이유는 개발언어에 대해 각기 새로운 면이 있기 때문에 통합하기 위해
하지만 가상환경 자체가 구동하는데 무겁기 때문에 이런 가상환경을 위해 container를 사용하게 되었다.
```

## Container는 linux를 기반으로 가상적인 공간을 만들어 준다.
VMware VS Docker Container   
- Docker가 좀 더 시간을 절약시켜 준다. 또한 memory의 사용량이 vmware에 비해 적다.

![1](C:\Users\jiyoung\Downloads\1.png)
 
	Monolith의 단점은 한꺼번에 해야 한다는 점(시간 오래 걸림)
	Microservices는 분산되어 있기 때문에 시간도 줄어들고, 각각 하나씩 맡기 때문에 인적자원 또한 여유 있다.
	또한 container를 따로 사용하기 때문에 독립적인 서비스를 제공할 수 있다. 한정된 자원 안에서 운영될 수 있다. (프로세스의 단순화를 위해 container를 많이 사용한다.)



