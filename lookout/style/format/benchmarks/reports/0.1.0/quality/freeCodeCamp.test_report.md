# Test report for javascript / file:///tmp/top-repos-quality-repos-hda3ai6m/freeCodeCamp HEAD cf65516cce60645a417e44c4fcea7418ca920572

### Classification report

PPCR: 0.904

| Class | Precision | Recall | Full Recall | F1-score | Full F1-score | Support | Full Support | PPCR |
|------:|:----------|:-------|:------------|:---------|:---------|:--------|:-------------|:-----|
| `∅` | 0.963| 0.994| 0.956| 0.978| 0.960| 11075| 11512| 0.962 |
| `␣` | 0.949| 0.946| 0.848| 0.947| 0.895| 4716| 5261| 0.896 |
| `'` | 0.952| 0.991| 0.966| 0.971| 0.959| 1405| 1442| 0.974 |
| `⏎` | 0.901| 0.806| 0.514| 0.851| 0.655| 1145| 1795| 0.638 |
| `⏎␣⁺␣⁺` | 0.881| 0.704| 0.640| 0.783| 0.741| 777| 855| 0.909 |
| `⏎␣⁻␣⁻` | 0.886| 0.861| 0.694| 0.873| 0.778| 575| 713| 0.806 |
| `␣'` | 0.973| 0.971| 0.950| 0.972| 0.961| 550| 562| 0.979 |
| `⏎⏎` | 0.898| 0.809| 0.513| 0.851| 0.653| 293| 462| 0.634 |
| `'⏎` | 1.000| 0.936| 0.603| 0.967| 0.753| 78| 121| 0.645 |
| `'␣` | 0.909| 0.682| 0.390| 0.779| 0.545| 44| 77| 0.571 |
| `⏎␣⁻␣⁻␣⁻␣⁻` | 0.000| 0.000| 0.000| 0.000| 0.000| 29| 36| 0.806 |
| `'⏎␣⁻␣⁻` | 0.000| 0.000| 0.000| 0.000| 0.000| 20| 60| 0.333 |
| `"` | 0.000| 0.000| 0.000| 0.000| 0.000| 5| 5| 1.000 |
| `macro avg` | 0.716| 0.669| 0.544| 0.690| 0.608| 20712| 22901| 0.904 |
| `weighted avg` | 0.947| 0.951| 0.860| 0.948| 0.894| 20712| 22901| 0.904 |
| `micro avg` | 0.951| 0.951| 0.860| 0.951| 0.903| 20712| 22901| 0.904 |

### Confusion matrix

|refusal|  ∅| ␣| ⏎| '| ⏎␣⁺␣⁺| ⏎␣⁻␣⁻| ␣'| ⏎⏎| '␣| '⏎| '⏎␣⁻␣⁻| "| ⏎␣⁻␣⁻␣⁻␣⁻| 
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|0 |0 |0 |0 |0 |0 |0 |0 |0 |0 |0 |0 |0 |0 |
|437 |11006 |50 |0 |0 |1 |18 |0 |0 |0 |0 |0 |0 |0 |
|545 |117 |4460 |42 |0 |73 |23 |0 |1 |0 |0 |0 |0 |0 |
|650 |67 |126 |923 |0 |0 |0 |3 |26 |0 |0 |0 |0 |0 |
|37 |1 |0 |0 |1393 |0 |0 |10 |0 |1 |0 |0 |0 |0 |
|78 |158 |50 |0 |20 |547 |0 |2 |0 |0 |0 |0 |0 |0 |
|138 |69 |9 |2 |0 |0 |495 |0 |0 |0 |0 |0 |0 |0 |
|12 |0 |4 |4 |8 |0 |0 |534 |0 |0 |0 |0 |0 |0 |
|169 |2 |1 |53 |0 |0 |0 |0 |237 |0 |0 |0 |0 |0 |
|33 |0 |0 |0 |14 |0 |0 |0 |0 |30 |0 |0 |0 |0 |
|43 |0 |0 |0 |3 |0 |0 |0 |0 |2 |73 |0 |0 |0 |
|40 |0 |0 |0 |20 |0 |0 |0 |0 |0 |0 |0 |0 |0 |
|0 |0 |0 |0 |5 |0 |0 |0 |0 |0 |0 |0 |0 |0 |
|7 |6 |0 |0 |0 |0 |23 |0 |0 |0 |0 |0 |0 |0 |

### Files with most errors

| filename | number of errors|
|:----:|:-----|

<details>
    <summary>Machine-readable report</summary>
```json
{
  "cl_report": {"\"": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 5}, "\u0027": {"f1-score": 0.9714086471408648, "precision": 0.9521531100478469, "recall": 0.9914590747330961, "support": 1405}, "\u0027\u23ce": {"f1-score": 0.9668874172185431, "precision": 1.0, "recall": 0.9358974358974359, "support": 78}, "\u0027\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 20}, "\u0027\u2423": {"f1-score": 0.7792207792207791, "precision": 0.9090909090909091, "recall": 0.6818181818181818, "support": 44}, "macro avg": {"f1-score": 0.6901949206470775, "precision": 0.7162723978994432, "recall": 0.6691859054298318, "support": 20712}, "micro avg": {"f1-score": 0.9510428736964078, "precision": 0.9510428736964078, "recall": 0.9510428736964078, "support": 20712}, "weighted avg": {"f1-score": 0.9484725385506224, "precision": 0.9473981863152069, "recall": 0.9510428736964078, "support": 20712}, "\u2205": {"f1-score": 0.9782676325496645, "precision": 0.9632417293891126, "recall": 0.9937697516930023, "support": 11075}, "\u23ce": {"f1-score": 0.851083448593822, "precision": 0.9013671875, "recall": 0.8061135371179039, "support": 1145}, "\u23ce\u23ce": {"f1-score": 0.850987432675045, "precision": 0.8977272727272727, "recall": 0.8088737201365188, "support": 293}, "\u23ce\u2423\u207a\u2423\u207a": {"f1-score": 0.7825464949928469, "precision": 0.8808373590982287, "recall": 0.703989703989704, "support": 777}, "\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.873015873015873, "precision": 0.8855098389982111, "recall": 0.8608695652173913, "support": 575}, "\u23ce\u2423\u207b\u2423\u207b\u2423\u207b\u2423\u207b": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 29}, "\u2423": {"f1-score": 0.9473237043330502, "precision": 0.948936170212766, "recall": 0.9457167090754877, "support": 4716}, "\u2423\u0027": {"f1-score": 0.9717925386715196, "precision": 0.9726775956284153, "recall": 0.9709090909090909, "support": 550}},
  "cl_report_full": {"\"": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 5}, "\u0027": {"f1-score": 0.9590361445783133, "precision": 0.9521531100478469, "recall": 0.9660194174757282, "support": 1442}, "\u0027\u23ce": {"f1-score": 0.7525773195876289, "precision": 1.0, "recall": 0.6033057851239669, "support": 121}, "\u0027\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 60}, "\u0027\u2423": {"f1-score": 0.5454545454545454, "precision": 0.9090909090909091, "recall": 0.38961038961038963, "support": 77}, "macro avg": {"f1-score": 0.6077473746740902, "precision": 0.7162723978994432, "recall": 0.5441627570926612, "support": 22901}, "micro avg": {"f1-score": 0.9033086465044825, "precision": 0.9510428736964078, "recall": 0.8601371119165102, "support": 22901}, "weighted avg": {"f1-score": 0.8943022966355582, "precision": 0.9435845654096415, "recall": 0.8601371119165102, "support": 22901}, "\u2205": {"f1-score": 0.9596303077862064, "precision": 0.9632417293891126, "recall": 0.9560458651841557, "support": 11512}, "\u23ce": {"f1-score": 0.6548421426037602, "precision": 0.9013671875, "recall": 0.5142061281337047, "support": 1795}, "\u23ce\u23ce": {"f1-score": 0.6528925619834711, "precision": 0.8977272727272727, "recall": 0.512987012987013, "support": 462}, "\u23ce\u2423\u207a\u2423\u207a": {"f1-score": 0.7411924119241192, "precision": 0.8808373590982287, "recall": 0.639766081871345, "support": 855}, "\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.7783018867924529, "precision": 0.8855098389982111, "recall": 0.6942496493688639, "support": 713}, "\u23ce\u2423\u207b\u2423\u207b\u2423\u207b\u2423\u207b": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 36}, "\u2423": {"f1-score": 0.8954924204397149, "precision": 0.948936170212766, "recall": 0.8477475765063676, "support": 5261}, "\u2423\u0027": {"f1-score": 0.9612961296129613, "precision": 0.9726775956284153, "recall": 0.9501779359430605, "support": 562}},
  "ppcr": 0.9044146543819047
}
```
</details>