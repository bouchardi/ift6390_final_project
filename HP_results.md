# CLEANED DATA

## HD
```
>>> MLP
valid score = 0.6569767441860466
test score = 0.6296296296296297 += 0.12880119369726653
{'hidden_layer_sizes': 150}

>>> LR
valid score = 0.8609936575052854
test score = 0.8518518518518519 += 0.09475220841136885
{'C': 0.5, 'penalty': 'l2'}

>>> RF
valid score = 0.8563424947145876
test score = 0.8518518518518519 += 0.09475220841136885
{'max_depth': 4, 'n_estimators': 50}
```

## CC
```
>>> RF
valid score = 0.956615419144877
test score = 0.9520958083832335 += 0.03239104207970507
{'max_depth': 10, 'n_estimators': 20}

>>> LR
valid score = 0.9610593648299854
test score = 0.9640718562874252 += 0.02822733827476049
{'C': 0.2, 'penalty': 'l1'}

>>> MLP
valid score = 0.9356413421613736
test score = 0.9341317365269461 += 0.03762183777250079
{'hidden_layer_sizes': 10}
```

# CLEANED + BALANCED DATA

## HD
```
>>> MLP
valid score = 0.6791666666666667
test score = 0.8166666666666667 += 0.0979092172107142
{'hidden_layer_sizes': (75, 75)}

>>> LR
valid score = 0.8208333333333334
test score = 0.85 += 0.0903515356814703
{'C': 0.1, 'penalty': 'l2'}

>>> RF
valid score = 0.8458333333333334
test score = 0.8333333333333334 += 0.09430054396763886
{'max_depth': 2, 'n_estimators': 75}
```

## CC
```
>>> MLP
valid score = 0.9479357429718875
test score = 0.9680511182108626 += 0.019483226495132736
{'hidden_layer_sizes': (50, 50)}

>>> LR
valid score = 0.9575550200803212
test score = 0.939297124600639 += 0.026453919687445537
{'C': 0.8, 'penalty': 'l1'}

>>> RF
valid score = 0.981574297188755
test score = 0.9776357827476039 += 0.01638133524543905
{'max_depth': 7, 'n_estimators': 30}
```

# CLEANED + BALANCED + FEATURE SELECTED DATA

## HD
```
>>> RF
valid score = 0.8458333333333334
test score = 0.8333333333333334 += 0.09430054396763886
{'max_depth': 2, 'n_estimators': 75}

>>> LR
valid score = 0.8208333333333334
test score = 0.85 += 0.0903515356814703
{'C': 0.1, 'penalty': 'l2'}

>>> MLP
valid score = 0.7000000000000001
test score = 0.7 += 0.11595516374875248
{'hidden_layer_sizes': (100, 100)}
```

## CC
```
>>> MLP
valid score = 0.9423261044176707
test score = 0.9584664536741214 += 0.02210405072546872
{'hidden_layer_sizes': (50, 50)}

>>> LR
valid score = 0.9575550200803212
test score = 0.939297124600639 += 0.026453919687445537
{'C': 0.8, 'penalty': 'l1'}

>>> RF
valid score = 0.981574297188755
test score = 0.9776357827476039 += 0.01638133524543905
{'max_depth': 7, 'n_estimators': 30}
```