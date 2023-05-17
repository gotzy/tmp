検索をさせないで、レコメンデーションさせる  
検索クエリはあまり増えないかもしれないが、レコメンデーションが発達すれば、  
そのレコメンデーションの根拠が検索クエリと同様に世の中の需要と考えられる。  
費用を安定性という形で登場させるか？  
ContentClickはその後の検索や広告クリックに繋がっていくだろうから、利益には貢献しそう。  
だがしかし、小出さんが指摘していた循環にならないようにツリー状で表現できるか？
  


```mermaid
flowchart TB
    
    a["Vision: ユーザー満足度"] --> c["NSM :安定的なマッチングの良さ"]
    b["KGI: 利益"]--> c
    c --> d["マッチングの良さ"]
    c --> e["安定性"]
    
    
    
    d --> f[" (ContentCllick + KwAdClick) / (ContentViewableImp + KwAdViewableImp)  "]
    f --> f1["検索"]
    f --> f2["非検索"]
    
    f1 --> g1[" ContentCllick_検索 "]
    f1 --> h1[" KwAdClick_検索 "]
    f1 --> i1[" ContentViewableImp_検索 "]
    f1 --> j1[" KwAdViewableImp_検索 "]
    
    f2 --> g2[" ContentCllick_非検索 "]
    f2 --> h2[" KwAdClick_非検索 "]
    f2 --> i2[" ContentViewableImp_非検索 "]
    f2 --> j2[" KwAdViewableImp_非検索 "]
    
    h1 --> k1[" cost_検索 "]
    h1 --> l1[" cpc_検索 "]
    
    h2 --> k2[" cost_非検索 "]
    h2 --> l2[" cpc_非検索 "]
    
    
    
    
    
    e --> y["費用"]
    y --> z1["メディアへの支払い</br>revenue"]
    y --> z2["インフラ費"]
    y --> z3["人件費"]
    y --> z4["その他"]
    
```



