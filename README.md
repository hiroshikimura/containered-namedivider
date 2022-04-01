### こんな感じ
```
> docker compose up -d
(この後エラーが出るけど気にしない)
> curl -X POST -H "Content-type: application/json" http://localhost:28000/divide -d '{"names":["島崎藤村", "滝廉太郎"]}'
{"divided_names":[{"family":"島崎","given":"藤村","separator":" ","score":0.3838098423116366,"algorithm":"kanji_feature"},{"family":"滝","given":"廉太郎","separator":" ","score":0.5304944367777146,"algorithm":"kanji_feature"}]}%
```

### 謝辞

- thanks lot!
  - https://github.com/rskmoi
    - https://github.com/rskmoi/namedivider-python
