### こんな感じ
```
> docker compose up -d
(この後エラーが出るけど(･з･)ｷﾆｽﾙﾅ!)
> curl -X POST -H "Content-type: application/json" http://localhost:28000/divide -d '{"names":["竈門炭治郎", "竈門禰豆子"]}'
{"divided_names":[{"family":"竈門","given":"炭治郎","separator":" ","score":0.3004587452426102,"algorithm":"kanji_feature"},{"family":"竈門","given":"禰豆子","separator":" ","score":0.30480429696983175,"algorithm":"kanji_feature"}]}%                                                                            
```