OpenAi MountainCar
==================


## Installation

    $ cd mountain_car
    $ python3 -m venv venv
    $ source venv/bin/activate

    (venv) $ pip install requirement.txt
    or
    (venv) $ pip install tensorflow theano keras gym matplotlib h5py



## Run

    $ python openai_example_mountaincar.py



## Description

 EPISODES 만큼 반복 학습하면서, reward를 줍니다.
 매 반복시마다 score에 reward를 더해주면서 score를 갱신시켜줍니다
 save_graph의 MountainCar_DQN.png를 보면 x축(EPISODES 수), y축(score)으로 EPISODES가 진행됨에 따라 score를 볼수 있습니다.

 이 예제는 episode 학습횟수가 많아야 변화양상을 볼 수 있습니다.