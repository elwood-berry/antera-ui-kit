
# 1. SELECT DATASET

```JSON
{
  "datasetName": [
    "Order Activity Report"
  ]
}
```






# 2. SELECT COLUMNS OF THE DATASET

These are the column names we need to display to the user.
```JSON
{
  "datasetName": "Order Activity Report",
  "friendlyColumnDataset": [
    "Sales Person",
    "New Sos",
    "Lines Typed",
    "Qty of Products",
    "Dollars of Product Sold",
    "COGS",
    "Margin $",
    "Avg Margin",
    "Average Sale",
    "Average Lines"
  ]
}
```


# 3. SELECT FILER (for every column)

Filters for **Sales Person**
```JSON
{
  "filterDataset": {
    "Sales Person": {
      "columnindex": 0,
      "type": "string",
      "conditionType": "group",
      "filters": [
        "equal",
        "betweenFirst",
        "betweenLast",
        "betweenAll"
      ]

    }
  }
}
```

Filters for **New Sos**
```JSON
{
  "filterDataset": {
    "Sales Person": {
      "columnindex": 1,
      "type": "number",
      "conditionType": "group",
      "filters": [
        "equal",
        "greater",
        "less",
        "greaterEqual",
        "lessEqual"
      ]

    }
  }
}
```

Filters for **Lines Typed**
```JSON
{
  "filterDataset": {
    "Sales Person": {
      "columnindex": 2,
      "type": "float",
      "conditionType": "group",
      "filters": [
        "equal",
        "greater",
        "less",
        "greaterEqual",
        "lessEqual"
      ]

    }
  }
}
```

Filters for **Qty of Products**
```JSON
{
  "filterDataset": {
    "Sales Person": {
      "columnindex": 3,
      "type": "number",
      "conditionType": "group",
      "filters": [
        "equal",
        "greater",
        "less",
        "greaterEqual",
        "lessEqual"
      ]

    }
  }
}
```

Filters for **Dollars of Product Sold**
```JSON
{
  "filterDataset": {
    "Sales Person": {
      "columnindex": 4,
      "type": "float",
      "conditionType": "group",
      "filters": [
        "equal",
        "greater",
        "less",
        "greaterEqual",
        "lessEqual"
      ]

    }
  }
}
```

Filters for **COGS**
```JSON
{
  "filterDataset": {
    "Sales Person": {
      "columnindex": 5,
      "type": "float",
      "conditionType": "group",
      "filters": [
        "equal",
        "greater",
        "less",
        "greaterEqual",
        "lessEqual"
      ]

    }
  }
}
```

Filters for **Margin $**
```JSON
{
  "filterDataset": {
    "Sales Person": {
      "columnindex": 6,
      "type": "float",
      "conditionType": "group",
      "filters": [
        "equal",
        "greater",
        "less",
        "greaterEqual",
        "lessEqual"
      ]

    }
  }
}
```

Filters for **Avg Margin**
```JSON
{
  "filterDataset": {
    "Sales Person": {
      "columnindex": 7,
      "type": "float",
      "conditionType": "group",
      "filters": [
        "equal",
        "greater",
        "less",
        "greaterEqual",
        "lessEqual"
      ]

    }
  }
}
```

Filters for **Average Sale**
```JSON
{
  "filterDataset": {
    "Sales Person": {
      "columnindex": 7,
      "type": "float",
      "conditionType": "group",
      "filters": [
        "equal",
        "greater",
        "less",
        "greaterEqual",
        "lessEqual"
      ]

    }
  }
}
```

Filters for **Average Lines**
```JSON
{
  "filterDataset": {
    "Sales Person": {
      "columnindex": 7,
      "type": "float",
      "conditionType": "group",
      "filters": [
        "equal",
        "greater",
        "less",
        "greaterEqual",
        "lessEqual"
      ]

    }
  }
}
```



# 4. SELECT SORTING
```JSON
{
  "sortDataset": [
    "ascending",
    "descending"
  ]
}
```



# 5. WHEN SHOULD THIS REPORT BE RUN?
