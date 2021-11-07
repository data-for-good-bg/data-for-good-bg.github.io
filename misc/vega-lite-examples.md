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

## BSP

[Fullscreen viz](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQAEySYUqUAwBOgtBmx5CBbUgDu1OoyYMIcbVDmY4szJUcICsmgGs2gtQZBOFgfGk5EJFcaKABRYKhMdlkIAmQIZ20CKKRBAE8IGlScbTgAM35iGgAvAiYIHAB9ACYABmaARncIYhAAXyUzGmV6NA621qV4GjIsNABOVsmQZG0fNFBMPJw4fSgaB2DFEDYcJH2ttFbKAA4lDO02H130JgCodfvMR+eAdWHRqgOkpHII2Np9ABiJAdDpMOH9JQuRzKGiyMgbEAAD0xZRocEEyj2UWUjVkDAQTHsxy2O304NRslyxyQWKKmLI2mGaDKuTsfQGIDyuPxhP0CAOZPBCBp2xeJ20jOZSlZ7M0ICSmCO6H6gsK1ReoDxBKJ6BK5UaxDYzggsrp6AAjgwopq1DRSMdoLlDSBTOi4ABZVloMRLVoCpSYNj+JI4NAAbSNotNK0lsmldvlDLRyo1dG1IEAOCCADBBAAQgiKTJuJslJ5Mp1Mjcvpipzekj+flgFwQQB8IIAeEEArCCAARAKyBjWL0EyELtG-aQOmJUy23mtfLAFgggAYQQC8IIAWEEAHCDb9eAIRAR2OU+aypbrXBbTP5U6XXQ3R72yv9IB8EEH-cAIiBD-ubwBiILuu79AAulMpRlCKVboMIsifBqTYTmwC7MhGICOLIeIYuqwRkC4pqgKiEBIG8LzfAwcACn0QA/view)

## ITN

[Fullscreen viz](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQAEySYUqUAwBOgtBmx5CBbUgDu1OoyYMIcbVDmY4szJUcICsmgGs2gtQZBOFgfGk5EJFcaKABRYKhMdlkIAmQIZ20CKKRBAE8IGlScbTgAM35iGgAvAjpZAH0AJgAGJoBGdwhiEABfJTMaZXo0dtaWpXgaMiw0AE4WiZBkbR80UEw8nDh9KBoHYMUQNhwkPc20FsoADiUM7TYfHfQmAKg1u8wHp4B1IZHUO0lI5BGxtPoAMRwFpQJBNJp9JQuRzKGiyMjrEAAD0xZRocEEyl2UWUDVkDAQTHsR02230YNRslyRyQWKKmLI2iGaDKuTsvX6IDyuPxhP0CH2ZLBCBpW2ex20jOZSlZ7M0ICSmEO6D6gsK1WeoDxBKJ6BK5QaxDYzggsrp6AAjgwopq1DRSEdoLlDSBTOi4ABZVloMSLFoCpSYNj+JI4NAAbSNotNy0lsmldvlDLRyo1dG1IEAOCCADBBAAQgiKTJuJslJ5Mp1Mjcvpipzekj+flgFwQQB8IIAeEEArCCAARAKyBjWL0EyEDtG-aQOmJUy23mtfLAFgggAYQQC8IIAWEEAHCDb9eAIRAR2OU+aypbrXBbTP5U6XXQ3R72yv9IB8EEH-cAIiBD-ubwBiILuu59AAupMpRlCKVboMIsgfBqTYTmwC7MhGICOLIeIYuqwRkC4pqgKiEBIK8zxfAwcACr0QA/view)

# 2021_07 

## GERB


```json 
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": "ГЕРБ - Разпределение на преференициалния вот - 11.07.2021",
  "data": {
    "url": "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/gerb_2021_07.csv"
  },
  "width": 1200,
  "height": 900,
  "mark": {
    "type": "circle",
    "opacity": 0.8,
    "stroke": "black",
    "strokeWidth": 1,
    "color": "#1c4d9c"
  },
  "encoding": {
    "x": {"field": "cand_number", "type": "ordinal", "axis": {"grid": false, "title": "Кандидат номер"}},
    "y": {"field": "mir_norm", "type": "ordinal", "axis": {"title": "МИР"}},
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
    "href": {"field": "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
```

[viz](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQmOoLhoQgZBBAqCCACEECIIAAJ+h3YAYQQOwggfhBAAiCBWEEAsIHcDcIHcC8IIA4QO4bdnDtu0AREDt7T0AxEA8zZ09AeRBDQCYQQD4QQCEQY0MARnTKAAYAdkoAJmyC9MUQABMkTBRUUAYAJ0ENLFx8InqkAHdqOkYmBgg4eqg5TDhZTEoRhAJZGgBrNkEqhjVYeZpORCQJmigAUTWVOQgCZAgx+oIdpEEATwgaU5x6uAAzfmIaAC8CMiGmAB9IolQF5KYQYggAC+Sk6NHK9DQ6SK2SU8BoZCwaAAnNk0SBkPV5mhQJg7jh1OgoDRhmoymwcEgaeS0NlKAAOJQXepseZUkBMZZQEnczC8-kAdQRSNQ6SUI0EbHqGgAxOkoAAWco4qAwpTjEblGiyMikkAAD3NbxocEE5Q0UB25UBsgYCCYQzK5MpGmVxtktzKSAtT3NZHqCLQb1ugyUKkw9PQgCwQMxuBweBxmVJuRKAHhAQjDYSA7tbbfaNAhaa7lQhvRSBf6TUGlCGw7VlKoBYAcEEAGCC6Ivcn5U0A2u0O9Avd6A4hsMYQeu+9AARwYOwTVRopDK0FuI5AHVNcAAsiG0GJ8dlocXMGwliocGgANqj8sTwnV2S1xeN+oBludomPb9vqr7jo6zquu6noqvGDZ+n+zZNPGXYaIAuCD5oWsJgRW6CBgg6hwUuIBflWgbIYBSYgKm6aZtmoEgGOuEgFObwznOcALkRAqruudCbtuKFARogD4IPYwShBEHgwgAuuirxvGW4HoMIsiiso8F4WwZFBteCpyDaZodmo-yyBOoDGhASBClS4oMHA17QkAA)
## ITN

```json
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": "ПП ИТН - Разпределение на преференициалния вот - 11.07.2021",
  "data": {
    "url": "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/itn_2021_07.csv"
  },
  "width": 1200,
  "height": 900,
  "mark": {
    "type": "circle",
    "opacity": 0.8,
    "stroke": "black",
    "strokeWidth": 1,
    "color": "#07abecc2"
  },
  "encoding": {
    "x": {"field": "cand_number", "type": "ordinal", "axis": {"grid": false, "title": "Кандидат номер"}},
    "y": {"field": "mir_norm", "type": "ordinal", "axis": {"title": "МИР"}},
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
    "href": {"field": "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
```

[viz](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQmOoLhoQgfBBNAAkAYIICIQQLggO-jsAEIIAYQQOwggfhBAAiCBWEEAsII8DcII8C8IIA4QRzs+WOg6OgCIgjk4+gGIg3pZuPoDyIDqATCCAfCCAQiCmOgCMWZQADADslABMecVZiiAAJkiYKKigDABOghpYuPhETUgA7tR0jEwMEHBNUHKYcLKYlOMIBLI0ANZsgrUMarBLNJyISNM0UACimypyEATIEJNNBPtIggCeEDQXOE1wAGb8xDQAXgQ6LIAPqlcrAwqzCDEEAAXyUPRoVXoaCypTySngNDIWDQAE48hiQMgmks0KBMI8cOp0FAaGM1JU2DgkHTKWg8pQABxKa5NNhLGkgJhrKBk3mYfmCgDqSJRqCySnGgjYTQ0AGJCkgmHAoFBinClFNxlUaLIyOSQAAPS2fGhwQRVDRQfZVYGyBgIHVqpSU6kaVWm2QPSpIK2vS1kJpItCfB4jX2qIWALBBLJ5nN5nJYMp4UoAeEHCcPhIEetvtjo0CHp7tVCEqfqFgbNIaUYYjDWUSY0gBwQPTmIu8-400B2h1O9DvL7A4hsSYQetUoUARwY+xUdRUpEq0Aew5A3XNcAAsmG0GJCXlYcXMGxViocGgANoj8vj4nV2S1hf+9BN4OtRNMEZdBe37eEXzHZ1XXdT1vW-RsmiDFtOyAoUjHzQtwJAUcK3QYMEHUX1Fw0T8q3-esu3QVN00zbNDQg3CQEnT5p1nOB5yIn8QBXNc6FqGgt0A4CtCcMIImibw4QAXUxD5PjLSD0GEWRxWUYi8LYMiQyvJU5DtC0OzUMgpnHUBTQgbVgMlBg4CvWEgA)

## BSP

```json
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": "БСП  - Разпределение на преференициалния вот - 11.07.2021",
  "data": {
    "url": "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/bsp_2021_07.csv"
  },
  "width": 1200,
  "height": 900,
  "mark": {
    "type": "circle",
    "opacity": 0.8,
    "stroke": "black",
    "strokeWidth": 1,
    "color": "#be0b0bc2"
  },
  "encoding": {
    "x": {"field": "cand_number", "type": "ordinal", "axis": {"grid": false, "title": "Кандидат номер"}},
    "y": {"field": "mir_norm", "type": "ordinal", "axis": {"title": "МИР"}},
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
    "href": {"field": "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
```

[viz](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQmOoLhoQgRBBAhCCB8EAAE+-vsAEIIAYQQOwggfhBAAiCBWEEAsIHcDcIHcC8IIA4QO-rdn9tu0AREDt7T0AxEA8zZ09AeRB9QCYQQD4QQCEQI30ARnTKAAYAdkoAJmyC9MUQABMkTBRUUAYAJ0ENLFx8InqkAHdqOkYmBgg4eqg5TDhZTEoRhAJZGgBrNkEqhjVYeZpORCQJmigAUTWVOQgCZAgx+oIdpEEATwgaU5x6uAAzfmIaAC8CJggcAB9IolQF5KYQYggAC+Sk6NHK9DQ6SK2SU8BoZCwaAAnNk0SBkPV5mhQJg7jh1OgoDRhmoymwcEgaeS0NlKAAOJQXepseZUkBMZZQEnczC8-kAdQRSNQ6SUI0EbHqGgAxEw4NkmFqoAUYUpxiNyjRZGRSSAAB7mt40OCCcoaKA7cqA2QMBAalVKcmUjTK42yW5lJAWp7msj1BFoN63Qbe1QCwBYIGY3A4PA4zKk3IlADwgIRhsJAd2ttvtGgQtNdyoQZR9Av9JqDShDYdqygTGkAOCCADBATAXuT8qaAbXaHegXu9AcQ2GMILWKQKAI4MHYqaoqUhlaC3IcgDqmuAAWRDaDE+Oy0MLmDYSxUODQAG1h6Wx4TK7Jq-PfegG4GmvHMHpdAez7WFn1HR1nVdd1PS-et6gDJt20AgVAFwQXN8zAkARzLdBAwQdRvQXDQPwrP9aw7dBk1TdNM31cDcJACc3inGc4DnIjvxAZdVzoKoaE3ACgJAXR7GCUIIg8GEAF10VeN4Swg9BhFkUVlGIvC2DIoNLwVOQbTNNs1DIcYx1AY0ICQIUqXFBg4EvaEgA)

## DB

```json
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": "ДБ  - Разпределение на преференициалния вот - 11.07.2021",
  "data": {
    "url": "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/db_2021_07.csv"
  },
  "width": 1200,
  "height": 900,
  "mark": {
    "type": "circle",
    "opacity": 0.8,
    "stroke": "black",
    "strokeWidth": 1,
    "color": "#aa03f8"
  },
  "encoding": {
    "x": {"field": "cand_number", "type": "ordinal", "axis": {"grid": false, "title": "Кандидат номер"}},
    "y": {"field": "mir_norm", "type": "ordinal", "axis": {"title": "МИР"}},
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
    "href": {"field": "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
```

[viz](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQmOoLhoQgFBBAiCAACXf12ACEEAMIIHYQQPwggARBArCCAWEBuBuEBuBeEEAcIDd0uTu6zcAiIDa27oBiIG4mju6A8iC6gEwggHwggEIgBroAjKmUAAwA7JQATJl5qYogACZImCiooAwAToIaWLj4RLVIAO7UdIxMDBBwtVBymHCymJRDCASyNADWbIIVDGqwszSciEhjNFAAoisqchAEyBAjtQRbSIIAnhA0xzi1cABm-MQ0AF4EpUwA+gUin8chMIMQQABfJTtGilehoVIFTJKeA0MhYNAATkyyJAyFqszQoEwNxw6nQUBogzUJTYOCQlJJaEylAAHEozrU2LNySAmIsoISOZguTyAOqw+GoVJKIaCNi1DQAYiQSEyAGYXqzIUpRkNSjRZGQiSAAB4ml40OCCUoaKBbUp-WQMBBMAYlElkjQKg2ya4lJCmh4msi1WFoF7XfpKFSYGnoQBYICYXHY3HYTMkXPFADwgQUhUJANwtVptGgQVKdCoQHtJvJ9hv9SkDweqylUvMAOCCADBAjPmOV9yaBLdbbegnq8-sQ2CMIDWvegAI4MLaxio0UglaDXQcgNpGuAAWUDaDEOMyEILmDYCxUODQAG0hyXR3iK7Iq3O67VfY223HOz2OpPiOdoOk6LpuoqMa1t634Ng0MbthogC4IDmeZQsBpboH6CDqNB84gO+5Z+ghf7xiASYpmmGZASAw5YSA44vJO05wLO+G8kuK50GuG6If+GiAPggtiBMEYRuJCAC6KLPC8xYgegwiyEKygwdhbDEf6F6ynIlrGq2ahkKMo6gAaEBIPy5IigwcAXhCQA)

## ДПС

```json
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": " ДПС - Разпределение на преференициалния вот - 11.07.2021",
  "data": {
    "url": "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/dps_2021_07.csv"
  },
  "width": 1200,
  "height": 900,
  "mark": {
    "type": "circle",
    "opacity": 0.8,
    "stroke": "black",
    "strokeWidth": 1,
    "color": "#4f667c"
  },
  "encoding": {
    "x": {"field": "cand_number", "type": "ordinal", "axis": {"grid": false, "title": "Кандидат номер"}},
    "y": {"field": "mir_norm", "type": "ordinal", "axis": {"title": "МИР"}},
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
    "href": {"field": "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
```

[viz](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQmOoLhoQAAkAoIIHwQQIQgm-psAEIIAYQQOwggfhBAAiCBWEEAsIHcDcIHcC8IIA4QO5rdnNtu0AREDt7T0AxEA8zZ09AeRBNQCYQQD4QQCEQI00ARnTKAAYAdkoAJmyC9MUQABMkTBRUUAYAJ0ENLFx8InqkAHdqOkYmBgg4eqg5TDhZTEoRhAJZGgBrNkEqhjVYeZpORCQJmigAUTWVOQgCZAgx+oIdpEEATwgaU5x6uAAzfmIaAC8CcrwAPpFEoAvJTCDEEAAXyUnRo5XoaHSRWySngNDIWDQAE5sqiQMh6vM0KBMHccOp0FAaMM1GU2DgkNSyWhspQABxKC71NjzSkgJjLKDErmYHl8gDq8MRqHSShGgjY9Q0AGIACxvABsmtyUGhSnGI3KNFkZBJIAAHua3jQ4IJyhooDtygDZAwEEwhmUyRSNErjbJbmUkBanuayPV4Wg3rdBkoVJg6ehAFggZjcDg8DjMqTciUAPCAhaEwkB3a22+0aBA011KhDe8n8-0moNKENh2rKVT8wA4IIAMEBMRa5P0poBtdod6Be7wBxDYYwg9d96AAjgwdgmqjRSGVoLcRyAOqa4ABZENoMR47JQ4uYNhLFQ4NAAbVH5YnBOrslri8b9QDLc7RMe37fVX3HR1nVdd1PWVeMGz9P9myaeMuw0QBcEHzQsYTAit0EDBB1DgpcQC-KtA2QwCkxAVN00zbNQJAMdcJAKc3hnOc4AXIj+VXdc6E3bcUKAjRdHsYJQgiDxoQAXTRV43jLcD0GEWQRWUeC8LYMig2veU5BtM0OzUMhxgnUBjQgJBBUpMUGDga8oSAA)

## ISMV

```json
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "title": "ИСБГ  - Разпределение на преференициалния вот - 11.07.2021",
  "data": {
    "url": "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/ismv_2021_07.csv"
  },
  "width": 1200,
  "height": 900,
  "mark": {
    "type": "circle",
    "opacity": 0.8,
    "stroke": "black",
    "strokeWidth": 1,
    "color": "#028d25"
  },
  "encoding": {
    "x": {"field": "cand_number", "type": "ordinal", "axis": {"grid": false, "title": "Кандидат номер"}},
    "y": {"field": "mir_norm", "type": "ordinal", "axis": {"title": "МИР"}},
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
    "href": {"field": "link", "type": "nominal"}
  },
  "config": {"legend": {"disable": true}}
}
```

[viz](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQmOoLhoQgDBBAhCCBEEEDIIAAJD-Q4AIQQAwggdhBA-CCABEECsIIBYQB4G4QB4F4QQBwgDwx4uG9g6AIiAOjt6AYiBeFq7egPIghoBMIIB8IIBCICaGAIyZlAAMAOyUAEy5RZmKIAAmSJgoqKAMAE6CGli4+ESNSADu1HSMTAwQcI1QcphwspiUYwgEsjQA1myCNQxqsIs0nIhIUzRQAKIbKnIQBMgQE40Ee0iCAJ4QNOc4jXAAZvzENABeBC8EMQAPolMrAgozCDEEAAXyU3RolXoaEyJVySngNDIWDQAE5chiQMhGos0KBMA8cOp0FAaKM1BU2DgkHTKWhcpQABxKK6NNiLGkgJirKBk3mYfmCgDqSJRqEySjGgjYjQ0AGJSlzKkUxHClJMxpUaLIyOSQAAPc0fGhwQSVDRQPaVYGyBgIJgjCqU6kaVXG2T3CpIC0vc1kRpItAfe7DJQqTCM9CALBALB4nF4nBZ0h5koAeEDCcPhIAe1tt9o0CHprtVCG9VKF-pNQaUIbD9WUqiFgBwQTRmIu8v400A2u0O9BvT7A4hsCYQeu+9AARwYewTNRopAq0Huw5AXVNcAAsiG0GJCblYcXMGwViocGgANoj8vj4nV2S1heNxoBludxMez7fUXzHR1nVdd1PTVeMGz9X9mxaeMuw0QBcEHzQt4VAit0EDBB1FgxcQE-KtAyQgCkxAVN00zbMQJAUccJAScPmnWc4HnQihRXNc6A3LdkMAjRAHwQRxQnCKIvDhABdTF3g+MswPQYRZHFZQ4NwthSKDK8lTkG0zQ7NQyEmcdQGNCAkBFGlJQYOAr1hIA)