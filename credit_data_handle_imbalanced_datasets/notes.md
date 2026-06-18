# Day 01: Imbalanced Dataset & Under-sampling

## Dataset Problem

The dataset had two classes:

```text
0 = Legit Transaction
1 = Fraud Transaction
```

Class distribution:

```text
Legit = 284315
Fraud = 492
```

This is a highly imbalanced dataset. A model may become biased toward the majority class.

## What I Did

Separated both classes and Took 492 random legit samples. Combined legit sample with fraud data.

Final balanced dataset:

```text
Legit = 492
Fraud = 492
```

## Key Learning

* Checked class distribution using `value_counts()`
* Learned why imbalanced data is a problem
* Used under-sampling to balance the dataset
* Created a new balanced dataset using `pd.concat()`

## Summary

Under-sampling reduces the majority class to match the minority class.
It helps the model learn both classes more fairly, but some majority class data is lost.
