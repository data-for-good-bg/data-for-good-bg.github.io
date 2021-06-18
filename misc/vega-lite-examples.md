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
  "width": 900,
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
    ]
  },
  "config": {"legend": {"disable": true}}
}
}
```
[Open the Chart in the Vega Editor](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQAEySYUqUAwBOgtBmx5CBbUgDu1OoyYMIcbVDmY4szJUcICsmgGs2gtQZBOFgfGk5EJFcaKABRYKhMdlkIAmQIZ20CKKRBAE8IGlScbTgAM35iGgAvAjJ7JgB9ACYABmaARncIYhAAXyUzGmV6NABOVtaleBoyLHHJpWRtHzRQTDycOH0oGgdgxRA2HCRdjbRWygAOJQztNh9t9CYAqFXbzHvHgHVh0dQOkpHII2Np9ABiDpQAAsyjGUH6ShcjmUNFkZDWIAAHpiyjQ4IJlDsospGrIGAgmPZDhstvpQajZLlDkgsUVMWRtMM0GVcnY+gMQHlcfjCfoEHsyaCEDTNk8jtpGcylKz2ZoQElMAd0P1BYVqk9QHiCUT0CVyo1iGxnBBZXT0ABHBhRTVqGikQ7QXKGkCmdFwACyrLQYkmrQFSkwbH8SRwaAA2kbRaaQBLtFLtDLI3L6Yq0cqNXRtSBADgggAwQQAEIIikybibJSeTKdTs-aFUq9JGi-LALgggD4QQA8IIBWEEAAiDVkDGsXoJkIbYt+WyNgSpkdwta+WALBBAAwggF4QQAsIIAOEF3m8AQiBjicp81lS3WuC2uf6J0uuhuj2dtf6QD4IMPB4AREBHg+3QAxEH3fd+gAXUFRxZDxDF1WCep60xVEICQF4nk+Bg4AFPogA)

## DPS
Minor changes only 

```json
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "data": {
    "url": "https://raw.githubusercontent.com/nikolatulechki/semanticElections/master/analysis/pref-viz/dps_2021.csv"
  },
  "width": 900,
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

    ]
  },
  "config": {"legend": {"disable": true}}
}
```

[Open the Chart in the Vega Editor](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQAEySYUqUAwBOgtBmx5CBbUgDu1OoyYMIcbVDmY4szJUcICsmgGs2gtQZBOFgfGk5EJFcaKABRYKhMdlkIAmQIZ20CKKRBAE8IGlScbTgAM35iGgAvAmU8AH0AJgAGJoBGdwhiEABfJTMaZXo0AE4WlqV4GjIsMYmlZG0fNFBMPJw4fSgaB2DFEDYcJB31tBbKAA4lDO02Hy30JgCoFZvMO4eAdSGR1HalI5BGxtPoAMRiMRQAAscAAbH0lC5HMoaLIyKsQAAPTFlGhwQTKbZRZQNWQMBBMewHdabfQg1GyXIHJBYoqYsjaIZoMq5Oy9fogPK4-GE-QIXZkkEIGkbR6HbSM5lKVnszQgJKYfboPqCwrVR6gPEEonoErlBrENjOCCyunoACODCimrUNFIB2guUNIFM6LgAFlWWgxBMWgKlJg2P4kjg0ABtI2i00gCXaKXaGWRuX0xVo5UaujakCAHBBABgggAIQRFJk3E2Sk8mU6nZ+0KpV6SNF+WAXBBAHwggB4QQCsIIABEGrIGNYvQTIQWxb8tkbAlTI7ha18sAWCCABhBALwggBYQQAcILvN4AhEDHE5T5rKlutcFtc-0TpddDdHs7a-0gHwQYeDwAiICPB9ugBiIPu+59AAuoKjiyHiGLqsEZAuKaoCohASDPI8HwMHAAq9EAA)