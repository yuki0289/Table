```mermaid
graph LR;
a --> b;
```

```mermaid
graph LR;
s{学生};
s --- t1[課題を提出する];
s --- t2[試験を受ける];
s --- t3[講義内で発言する];

subgraph 成績評価;
t1;
t2;
t3;
end;
```
