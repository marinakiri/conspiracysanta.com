## Conspiracy Santa Email Generator

A simple Bottle.py + React.js app that sends emails to start a round of conspiracy santa.

```python
mkvirtualenv conspiracysanta
workon conspiracysanta
pip install -r requirements.txt
gunicorn conspiracy:app --bind=0.0.0.0:5000 --reload --log-file -
open "http://localhost:5000/"
```

And that's all there is!
