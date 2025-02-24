```python

def get_energy_level():
    day = datetime.now().strftime("%A")

    if day == "Friday":
        return "100%"  # Partytime
    elif day == "Monday":
        return "5%"   # The ultimate Hangover
    elif day == "Tuesday":
        return "40%"  # Slightly better than Monday, but still recovering
```


