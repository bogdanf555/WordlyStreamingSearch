# Search for a title worldwide on streaming services

## Dependencies

Run:

```
pip install -r requirement.txt
```

## How to use

Run:

```
python main.py '2001: A Space Odyssey'
```

The title should ideally be exactly as it appears on the JustWatch website when you search for your movie.<br>
Example ---  the movie TÁR has this special unicode in the middle that should appear in the search.<br>
Use quotes for more than 1 word titles.
<br><br>
Results will be visible at the end in a json file named after the title of the movie, inside a results directory:

Example
```
results/2001_A_Space_Odyssey.json
```

## Enjoy!
