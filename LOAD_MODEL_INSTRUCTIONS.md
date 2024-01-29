1. Make sure the model ("team58_model.h5") is in the same folder
2. Run this python script

```python
def load_model():
  loaded_model = joblib.load('./team58_model.h5')
  return loaded_model
  
loaded_model = load_model()
```
