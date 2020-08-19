## Bio-informatic
# Order 0~2
  1.讀進data手動查詢目標在第幾行，並設為"beginline"&"endline"
  2.統計各ATCG組合出現的次數在算出機率
  3.將機率取log2在相加

# HMM
  1.定義好transition and emmision matrix
  2.使用viterbi演算法算出何種state轉換能達到最大機率
