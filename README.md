# Unix-parallel-processing-project
<img width="672" alt="image" src="https://user-images.githubusercontent.com/121723421/210159261-e45c4d7e-d42f-4470-9a2a-aea5f3236b29.png">
4개의 compute노드에서 두개의 입출력 노드로 병렬적으로 데이터를 송신하고, ionode는 파이프를 이용해서 compute노드와 통신한다. compute노드에서 각각 데이터를 다른 3개의 compute로부터 모아서
ionode로 보내야 한다.
