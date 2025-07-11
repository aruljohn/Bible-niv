# Bible-niv

- This repository contains the NIV version of the Bible in JSON format.
- There are 66 books. Each book is a separate JSON file.
- Included is a JSON array of all 66 book names.

## Example JSON verse
As an example, this is Psalms 23 verse 1 in JSON format.

```
{
   "book": "Psalms",
   "count": "150",
   "chapters": [
      {
        .......
         "chapter": 23,
         "verses": [
            {
               "verse": 1,
               "text": "The Lord is my shepherd, I lack nothing."
            },
            .....
         ]
      }
   ]
}
```

## Books.json

`Books.json` is a JSON array containing all the 66 books of the NIV Bible.

This is a sample of `Books.json`.

```
[
   "Genesis",
   "Exodus",
   "Leviticus",
   "Numbers",
   "Deuteronomy",
   "Joshua",
   "Judges",
   "Ruth",
   "1 Samuel",
   "2 Samuel",
    ....
   "2 John",
   "3 John",
   "Jude",
   "Revelation"
]
```
