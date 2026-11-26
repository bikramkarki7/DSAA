
## 1. Normalization

Normalization is a data preprocessing technique used to scale numerical data into a fixed range, usually between 0 and 1.

It helps to make data values comparable and prevents large values from dominating smaller values during analysis.

### Types of Normalization

**1. Min-Max Normalization**
- It converts data values into a fixed range, usually 0 to 1.
- The minimum value becomes 0, and the maximum value becomes 1.

**Formula:**
```text
X' = (X - Xmin) / (Xmax - Xmin)
```

**2. Decimal Scaling Normalization**
- It normalizes data by moving the decimal point of values.
- It makes all values smaller than 1.

**Formula:**
```text
X' = X / 10^j
```

**3. Z-Score Normalization**
- It converts data based on the mean and standard deviation.
- The transformed data has a mean of 0 and a standard deviation of 1.

**Formula:**
```text
X' = (X - Mean) / Standard Deviation
```

---

## 2. Short Note on Standardization

Standardization is a data preprocessing technique used to transform data so that it has a mean of 0 and a standard deviation of 1.

It helps to bring data values onto a common scale, making it easier to compare and analyze them.

**Formula:**
```text
Z = (X - Mean) / Standard Deviation
```

**Advantages of Standardization:**
1. Makes data easier to compare.
2. Helps machine learning algorithms work effectively.
3. Reduces the effect of different measurement scales.
4. Useful when data has different ranges.

