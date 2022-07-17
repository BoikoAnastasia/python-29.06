
## Изучение работы Kroki

Kroki предоставляет унифицированный API с поддержкой BlockDiag (BlockDiag, SeqDiag, ActDiag, NwDiag, PacketDiag, RackDiag), BPMN, Bytefield, C4 (с PlantUML), Ditaa, Erd, Excalidraw, GraphViz, Mermaid, Nomnoml, Pikchr, PlantUML, Structurizr. , SvgBob, UMLet, Vega, Vega-Lite, WaveDrom... и многое другое!

Пример работы Kroki:

```graphviz
digraph finite_state_machine {
  rankdir=LR;
  node [shape = doublecircle]; LR_0 LR_3 LR_4 LR_8;
  node [shape = circle];
  LR_0 -> LR_2 [ label = "SS(B)" ];
  LR_0 -> LR_1 [ label = "SS(S)" ];
  LR_1 -> LR_3 [ label = "S($end)" ];
  LR_2 -> LR_6 [ label = "SS(b)" ];
  LR_2 -> LR_5 [ label = "SS(a)" ];
  LR_2 -> LR_4 [ label = "S(A)" ];
  LR_5 -> LR_7 [ label = "S(b)" ];
  LR_5 -> LR_5 [ label = "S(a)" ];
  LR_6 -> LR_6 [ label = "S(b)" ];
  LR_6 -> LR_5 [ label = "S(a)" ];
  LR_7 -> LR_8 [ label = "S(b)" ];
  LR_7 -> LR_5 [ label = "S(a)" ];
  LR_8 -> LR_6 [ label = "S(b)" ];
  LR_8 -> LR_5 [ label = "S(a)" ];
}
```

## Изучение работы microsoft threat modeling tool

Средство моделирования угроз — это основной элемент жизненного цикла Microsoft Security Development (SDL). Это позволяет разработчикам программного обеспечения выявлять и устранять потенциальные проблемы безопасности на ранней стадии, когда их решение относительно просто и рентабельно. В результате это значительно снижает общую стоимость разработки. Кроме того, мы разработали этот инструмент с расчетом на неспециалистов по безопасности, что упрощает моделирование угроз для всех разработчиков, предоставляя четкие рекомендации по созданию и анализу моделей угроз.

![Пример microsoft threat modeling](01.png "Пример microsoft threat modeling")


## Литература

https://kroki.io/
https://docs.gitlab.com/ee/administration/integration/kroki.html
https://docs.microsoft.com/en-us/azure/security/develop/threat-modeling-tool



