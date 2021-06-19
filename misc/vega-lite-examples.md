## Parties and mandates

```json
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": "Рисков вот: Разлика мандати по партия",
  "data": {
    "values": [
      {"a": "БСП", "b": 3, "c": "#9c271c"},
      {"a": "ГЕРБ", "b": 2, "c": "#1c4d9c"},
      {"a": "ДБ", "b": 1, "c": "#9f0ce8"},
      {"a": "ДПС", "b": -7, "c": "#55c4e6"},
      {"a": "ИСМВ", "b": 0, "c": "#258a36"},
      {"a": "ИТН", "b": 1, "c": "#e6ba0b"}
    ]
  },
  "width": 600,
  "height": 400,
  "mark": "bar",
  "encoding": {
    "x": {
      "field": "a",
      "type": "nominal",
      "axis": {"labelAngle": 90},
      "title": "партия"
    },
    "y": {"field": "b", "type": "quantitative", "title": "мандати"},
    "color": {"field": "a", "scale": {"range": {"field": "c"}}},
    "tooltip": [
      {"field": "a", "type": "nominal", "title": "Партия"},
      {"field": "b", "type": "quantitative", "title": "Мандати"}
    ]
  },
  "config": {"legend": {"disable": true}}
}
```
[Open the Chart in the Vega Editor](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQmOoLhoQgAhBAHCCBBEEBcIID4QQEwgAAmOHAQiCpTmwAwggdhBA3CDb9d04B4QO4F4QQCwgdy21TQH4QQxC7QAEQQMB5EEUQABMkTBRUUGIkQQY4CDQAbVAUkEBEEEBCEEB8EDimNABmJSgNAGIATigAJgB2AEZ6gF8FAo1AZBBAVBBNIsq0VrrG7oAWeJaQPoH0QBQQcaUq1E7p9GaAMwAGKDgADiX+kELVspKJ1H523ZAGsTEoWbgANguVkEAMEBKgBwQQBIIPdDs8Gq0xKckNUfssrhp-oAiEEAuCD3HYgep7b5MJCHKo9AC6fRAAHcaPF6GgvocIRg4DQyFg0LN6UpkAAnADWGnxXLicFkUDY8RosjIaFAAA9pSB9jQ4IJ4hoUEpMABPHDqdCyNgICUZOJIGU0HKpECCJBMZUAQUlajQTUOZJUmCd6GCkRiFxAmvliuVqvQVQ12t1IAAjgwkLJ3UkaKQ4u7PSAvH4Ato-aLBGxBZagyq1XFoBldaAuXGyBWFUri+hej03Ww2IIVDg8qAiyGkeGdRp9YbZMaNapI2UfdpYoie-yUxGNDG4wmVMmxx7I0CfP5AktSXU5IqpZa1DXZCHQOKIDbPZguVlmz0gA)
# Candidate Preferences

The data is [here](https://github.com/nikolatulechki/semanticElections/tree/master/analysis/pref-viz)

## GERB

```json
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "data": {
    "url": "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/gerb_2021.csv"
  },
  "width": 1200,
  "height": 900,
  "mark": {
    "type": "circle",
    "opacity": 0.8,
    "stroke": "black",
    "strokeWidth": 1,
    "color":"#1c4d9c"
  },
  "encoding": {
    "x": {"field": "cand_number", "type": "ordinal", "axis": {"grid": false}},
    "y": {"field": "mir_norm", "type": "ordinal", "axis": {"title": ""}},
    "size": {
      "field": "pref_votes",
      "type": "quantitative",
      "scale": {"rangeMax": 5000}
    },
    "tooltip": [
      {"field": "mir_norm", "type": "ordinal", "title": "МИР"},
      {"field": "cand_number", "type": "ordinal", "title": "Номер"},
      {"field": "name", "type": "nominal", "title": "Кандидат"},
      {"field": "pref_votes", "type": "quantitative", "title": "Преференции"}
    ],
    "href" : {"field" : "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
```

[Open the Chart in the Vega Editor](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQAEySYUqUAwBOgtBmx5CBbUgDu1OoyYMIcbVDmY4szJUcICsmgGs2gtQZBOFgfGk5EJFcaKABRYKhMdlkIAmQIZ20CKKRBAE8IGlScbTgAM35iGgAvAjJ7JgB9ACYABmaARncIYhAAXyUzGmV6NA621qV4GjIsNABOVsmQZG0fNFBMPJw4fSgaB2DFEDYcJH2ttFbKAA4lDO02H130JgCodfvMR+eAdWHRqgOkpHII2Np9ABiDpQAAsynmUH6ShcjmUNFkZA2IAAHtiyjQ4IJlHsospGrIGAgmPZjlsdvpwejZLljkgcUVsWRtMM0GVcnY+gMQHl8YTifoEAcKeCEHTti8TtpmaylOzOZoQElMEd0P1hYVqi9QASiST0CVyo1iGxnBB5Qz0ABHBhRbVqGikY7QXLGkCmTFwACy7LQYiWrSFSkwbH8SRwaAA2ibxeaVtLZLKHYqmRjVVq6LqQIAcEEAGCCAAhBkSmzaTZOTKdTadGFYzlXm9NHC4rALgggD4QQA8IIBWEEAAiBVkCmiXoFkIXbNx0gTNSlkdgs6xWALBBAAwggF4QQAsIIAOEF3m8AQiBjidpy1la22uD2ueKl1uuger2dtf6QD4IMPB4AREBHg+3QAxEH3fd+gAXSmUoyjFGt0GEWRPi1FspzYJdWSjEBHFkAksU1YJ6jrbF0QgJA3heb4GDgIU+iAA)

[fullscreen viz](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQAEySYUqUAwBOgtBmx5CBbUgDu1OoyYMIcbVDmY4szJUcICsmgGs2gtQZBOFgfGk5EJFcaKABRYKhMdlkIAmQIZ20CKKRBAE8IGlScbTgAM35iGgAvAjJ7JgB9ACYABmaARncIYhAAXyUzGmV6NA621qV4GjIsNABOVsmQZG0fNFBMPJw4fSgaB2DFEDYcJH2ttFbKAA4lDO02H130JgCodfvMR+eAdWHRqgOkpHII2Np9ABiDpQAAsynmUH6ShcjmUNFkZA2IAAHtiyjQ4IJlHsospGrIGAgmPZjlsdvpwejZLljkgcUVsWRtMM0GVcnY+gMQHl8YTifoEAcKeCEHTti8TtpmaylOzOZoQElMEd0P1hYVqi9QASiST0CVyo1iGxnBB5Qz0ABHBhRbVqGikY7QXLGkCmTFwACy7LQYiWrSFSkwbH8SRwaAA2ibxeaVtLZLKHYqmRjVVq6LqQIAcEEAGCCAAhBkSmzaTZOTKdTadGFYzlXm9NHC4rALgggD4QQA8IIBWEEAAiBVkCmiXoFkIXbNx0gTNSlkdgs6xWALBBAAwggF4QQAsIIAOEF3m8AQiBjidpy1la22uD2ueKl1uuger2dtf6QD4IMPB4AREBHg+3QAxEH3fd+gAXSmUoyjFGt0GEWRPi1FspzYJdWSjEBHFkAksU1YJ6jrbF0QgJA3heb4GDgIU+iAA/view)


## DPS
Minor changes only 

```json
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "data": {
    "url": "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/dps_2021.csv"
  },
  "width": 1200,
  "height": 900,
  "mark": {
    "type": "circle",
    "opacity": 0.8,
    "stroke": "black",
    "strokeWidth": 1,
    "color":"#55c4e6"
  },
  "encoding": {
    "x": {
      "field": "cand_number",
      "type": "ordinal",
      "axis": {"grid": false}
    },
    "y": {"field": "mir_norm", "type": "ordinal", "axis": {"title": ""}},
    "size": {
      "field": "pref_votes",
      "type": "quantitative",
      "scale": {"rangeMax": 5000}
    },
    "tooltip": [
      {"field": "mir_norm", "type": "ordinal", "title": "МИР"},
      {"field": "cand_number", "type": "ordinal", "title": "Номер"},
      {"field": "name", "type": "nominal", "title": "Кандидат"},
      {"field": "pref_votes", "type": "quantitative", "title": "Преференции"}

    ],
    "href" : {"field" : "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
```

[Open the Chart in the Vega Editor](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQAEySYUqUAwBOgtBmx5CBbUgDu1OoyYMIcbVDmY4szJUcICsmgGs2gtQZBOFgfGk5EJFcaKABRYKhMdlkIAmQIZ20CKKRBAE8IGlScbTgAM35iGgAvAmU8AH0AJgAGJoBGdwhiEABfJTMaZXo0dtaWpXgaMiw0AE4WiZBkbR80UEw8nDh9KBoHYMUQNhwkPc20FsoADiUM7TYfHfQmAKg1u8wHp4B1IZHUO0lI5BGxtPoAMRiMRQAAscAAbH0lC5HMoaLIyOsQAAPbFlGhwQTKXZRZQNWQMBBMexHTbbfRg9GyXJHJA4orYsjaIZoMq5Oy9fogPL4wnE-QIfYUsEIOlbZ7HbTM1lKdmczQgJKYQ7oPrCwrVZ6gAlEknoErlBrENjOCDyhnoACODCi2rUNFIR2guWNIFMmLgAFl2WgxIsWkKlJg2P4kjg0ABtE3i83LaWyWUOxVMjGqrV0XUgQA4IIAMEEABCDIlNm0mycmU6m06MKxnKvN6aOFxWAXBBAHwggB4QQCsIIABECrIFNEvQLIQO2bjpAmalLI7BZ1isAWCCABhBALwggBYQQAcILvN4AhEDHE7TlrK1ttcHtc8VLrddA9Xs7a-0gHwQYeDwAiICPB9ugBiIPu+59AAupMpRlGKNboMIsgfFqLZTmwS6slGICOLIBJYpqwRkC45qgOiEBIK8zxfAwcBCr0QA)

[Fullscreen viz](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQAEySYUqUAwBOgtBmx5CBbUgDu1OoyYMIcbVDmY4szJUcICsmgGs2gtQZBOFgfGk5EJFcaKABRYKhMdlkIAmQIZ20CKKRBAE8IGlScbTgAM35iGgAvAmU8AH0AJgAGJoBGdwhiEABfJTMaZXo0dtaWpXgaMiw0AE4WiZBkbR80UEw8nDh9KBoHYMUQNhwkPc20FsoADiUM7TYfHfQmAKg1u8wHp4B1IZHUO0lI5BGxtPoAMRiMRQAAscAAbH0lC5HMoaLIyOsQAAPbFlGhwQTKXZRZQNWQMBBMexHTbbfRg9GyXJHJA4orYsjaIZoMq5Oy9fogPL4wnE-QIfYUsEIOlbZ7HbTM1lKdmczQgJKYQ7oPrCwrVZ6gAlEknoErlBrENjOCDyhnoACODCi2rUNFIR2guWNIFMmLgAFl2WgxIsWkKlJg2P4kjg0ABtE3i83LaWyWUOxVMjGqrV0XUgQA4IIAMEEABCDIlNm0mycmU6m06MKxnKvN6aOFxWAXBBAHwggB4QQCsIIABECrIFNEvQLIQO2bjpAmalLI7BZ1isAWCCABhBALwggBYQQAcILvN4AhEDHE7TlrK1ttcHtc8VLrddA9Xs7a-0gHwQYeDwAiICPB9ugBiIPu+59AAupMpRlGKNboMIsgfFqLZTmwS6slGICOLIBJYpqwRkC45qgOiEBIK8zxfAwcBCr0QA/view)


## DB

```json
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "data": {
    "url": "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/db_2021.csv"
  },
  "width": 1200,
  "height": 900,
  "mark": {
    "type": "circle",
    "opacity": 0.8,
    "stroke": "black",
    "strokeWidth": 1,
    "color": "#7c189e" 
  },
  "encoding": {
    "x": {"field": "cand_number", "type": "ordinal", "axis": {"grid": false}},
    "y": {"field": "mir_norm", "type": "ordinal", "axis": {"title": ""}},
    "size": {
      "field": "pref_votes",
      "type": "quantitative",
      "scale": {"rangeMax": 5000}
    },
    "tooltip": [
      {"field": "mir_norm", "type": "ordinal", "title": "МИР"},
      {"field": "cand_number", "type": "ordinal", "title": "Номер"},
      {"field": "name", "type": "nominal", "title": "Кандидат"},
      {"field": "pref_votes", "type": "quantitative", "title": "Преференции"}
    ],
    "href" : {"field" : "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
```
[Open the Chart in the Vega Editor](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQAEySYUqUAwBOgtBmx5CBbUgDu1OoyYMIcbVDmY4szJUcICsmgGs2gtQZBOFgfGk5EJFcaKABRYKhMdlkIAmQIZ20CKKRBAE8IGlScbTgAM35iGgAvAmUmAH0AJgAGJoBGdwhiEABfJTMaZXo0dtaWpXgaMiw0AE4WiZBkbR80UEw8nDh9KBoHYMUQNhwkPc20FsoADiUM7TYfHfQmAKg1u8wHp4B1IZHUO0lI5BGxtPoAMQAdig7Wucx2-RALkcyhosjI6xAAA8sWUaHBBMpdlFlA1ZAwEEx7EdNtt9GC0bJckckNiiliyNohmgyrk7L0kXk8QSifoEPtyWCELSts9jtomSylGyOZoQElMId0H0kYVqs9QPjCcT0CVyg1iGxnBBZfT0ABHBhRTVqGikI7QXKGkCmDFwACybLQYkWLUFSkwbH8SRwaAA2kbRablpLZNK7fLGejlRq6NqQIAcEEAGCCAAhA+gokyaSbIyRSqTTI3KGYqc3pI-n5YBcEEAfCCAHhBAKwggAEQCtVsXoZkIHZN+0gdMS5ntvNa+WALBBAAwggF4QQAsIIAOEG368AQiCjkDG8cgc1lS3WuC2mfyp0uuhuj0dlf6QD4IEOB4AREGHA83QAxEF3Xc+gAXUmUoyhFat0GEWQPg1ZsJzYBcWQjEBHFkfFMXVYIyBcU1QDRCAkFeZ4vgYOBBV6IA)
[Fullscreen viz](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQAEySYUqUAwBOgtBmx5CBbUgDu1OoyYMIcbVDmY4szJUcICsmgGs2gtQZBOFgfGk5EJFcaKABRYKhMdlkIAmQIZ20CKKRBAE8IGlScbTgAM35iGgAvAmUmAH0AJgAGJoBGdwhiEABfJTMaZXo0dtaWpXgaMiw0AE4WiZBkbR80UEw8nDh9KBoHYMUQNhwkPc20FsoADiUM7TYfHfQmAKg1u8wHp4B1IZHUO0lI5BGxtPoAMQAdig7Wucx2-RALkcyhosjI6xAAA8sWUaHBBMpdlFlA1ZAwEEx7EdNtt9GC0bJckckNiiliyNohmgyrk7L0kXk8QSifoEPtyWCELSts9jtomSylGyOZoQElMId0H0kYVqs9QPjCcT0CVyg1iGxnBBZfT0ABHBhRTVqGikI7QXKGkCmDFwACybLQYkWLUFSkwbH8SRwaAA2kbRablpLZNK7fLGejlRq6NqQIAcEEAGCCAAhA+gokyaSbIyRSqTTI3KGYqc3pI-n5YBcEEAfCCAHhBAKwggAEQCtVsXoZkIHZN+0gdMS5ntvNa+WALBBAAwggF4QQAsIIAOEG368AQiCjkDG8cgc1lS3WuC2mfyp0uuhuj0dlf6QD4IEOB4AREGHA83QAxEF3Xc+gAXUmUoyhFat0GEWQPg1ZsJzYBcWQjEBHFkfFMXVYIyBcU1QDRCAkFeZ4vgYOBBV6IA/view)
