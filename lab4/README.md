1. Реализовать класс DecisionTree. 
В классе **должны** быть методы
```python
def __init__(..., classification:bool=true, ...):
    # some code
def predict(...):
    # some code
def fit(...):
    # some code
```
2. Реализовать класс RandomForest. 
В классе **должны** быть методы
```python
def __init__(..., classification:bool=true, ...):
    # some code
def predict(...):
    # some code
def fit(...):
    # some code
```
3. Реализовать класс GradientBoosting. 
В классе **должны** быть методы
```python
def __init__(..., classification:bool=true, ...):
    # some code
def predict(...):
    # some code
def fit(...):
    # some code
```
4. Обучить модели каждого алгоритма на следующих датасетах (проводим мини-соревнование между ними):
    * регрессия: https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset
    * классификация: https://www.kaggle.com/datasets/pankrzysiu/cifar10-python

5. Объяснить, почему алгоритм $A$ "победил", а почему алгоритм $B$ "проиграл".
