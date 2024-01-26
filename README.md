# Quran dataset
General information about the surahs of the Quran.

## Source
* [`quran.json`](https://github.com/ehsan-shahbakhsh/quran-dataset/blob/main/quran.json)


## Sample data
```json
{
  "1": {
    "name": "فاتحه",
    "alphabet": 63,
    "verses": 7,
    "descending_order": {
      "ابن عباس": 5,
      "نولدکه": 48
    },
    "landing_place": "مکه",
    "words": 29,
    "letters": 142,
    "other_name": "حمد",
    "content": [
      "خداشناسی",
      "معادشناسی",
      "راهنماشناسی"
    ]
  }
}
```

## About the data
* key: 1 => The number one surah of the Qur'an
* name: فاتحه => Surah name
* alphabet: 63 => In alphabetical order
* verses: 7 => The number of verses of the surah
* descending_order: ابن عباس: 5, نولدکه: 48 => Descending order based on two great characters
* landing_place: مکه => The place where this surah was revealed
* words: 29 => The number of words in this surah
* letters: 142 => The number of letters of this surah
* other_name: حمد => Another name of this surah
* content: خداشناسی, معادشناسی, راهنماشناسی => The content mentioned in this surah


## License
The quran-dataset library has an MIT license. You can read this file [LICENSE](LICENSE) for more information.
