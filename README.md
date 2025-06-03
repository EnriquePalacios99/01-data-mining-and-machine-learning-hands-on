# 01-data-mining-and-machine-learning-hands-on





En caso desees crear semanas consecutivas te dejo un código que puedes aplicar en terminal


```
for i in $(seq 1 16); do
    printf -v folder_num "%02d" $i
    mkdir "SEMANA${folder_num}"
done

```