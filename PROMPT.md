# 한의학 고전 중국어 → 한국어 번역

아래 JSON의 각 문장(original)을 한국어로 번역해주세요.

## 규칙
1. 고전 중국어(繁體字)를 자연스러운 현대 한국어로 번역
2. 한의학 전문 용어는 한국 한의학계 표준 용어 사용
3. 약재명은 한국식 명칭 + 한자 병기 (예: 당귀(當歸))
4. 처방 구성은 원문 그대로 + 한글 독음 병기
5. 번역 불확실 시 [?] 표시

## 입력
```json
[
  {
    "id": 4757583,
    "original": "皮之部也，是故百病之始生也，必先客于皮毛，邪中之則腠理開，開則入客于絡脈，留而不去，傳入于經，留而不去，傳入于腑，稟于腸胃。",
    "reading_ko": null,
    "book": "zhenjiujiayijing-針灸甲乙經",
    "category": "저작-zhuzuo-著作"
  },
  {
    "id": 3401524,
    "original": "邵評∶邪初入肺則在衛．不解．則入氣分．氣分不解．則傳心營．營不解．則入下焦血分矣．邪在血分．入里極深．中焦俱病．陰液受戕．每多液涸內閉之候．宜救陰達邪清營涼血治之．至于膻中．是包絡所居．在于上焦．用藥宜清輕而忌重濁．",
    "reading_ko": null,
    "book": "shanghanzhizhang-傷寒指掌",
    "category": "저작-zhuzuo-著作"
  },
  {
    "id": 3369817,
    "original": "發汗若下．不能盡其邪．而反傷其正．于是正氣欲復而不得復．邪氣雖微而不即去．正邪交爭．乃生煩躁．是不可更以麻、桂之屬逐其邪．及以梔、豉之類止其煩矣．是方干姜、生附之辛．",
    "reading_ko": null,
    "book": "shanghanguanzhuji-傷寒貫珠集",
    "category": "저작-zhuzuo-著作"
  },
  {
    "id": 3737542,
    "original": "男子、婦人咽爛者，靈藥一錢加人中白二分研細吹之，日用三次，內服不二散，其疼即止，隨可飲食。",
    "reading_ko": null,
    "book": "waikezhengzong-外科正宗",
    "category": "저작-zhuzuo-著作"
  },
  {
    "id": 3015879,
    "original": "種子丸，（五月五日拔益母草帶根陰干為末，煉蜜為丸，如彈子大，每朝二丸，百日必效。",
    "reading_ko": null,
    "book": "lengluyihua-冷廬醫話",
    "category": "저작-zhuzuo-著作"
  },
  {
    "id": 4412634,
    "original": "次則視岐，睹一成二，神水淡白色，可為沖和養胃湯主之，益氣聰明湯主之，《千金》磁朱丸主之，石斛夜明丸主之。",
    "reading_ko": null,
    "book": "yuanjiqiwei-原機啟微",
    "category": "저작-zhuzuo-著作"
  },
  {
    "id": 2455897,
    "original": "人參（三錢） 黃 （一兩） 當歸（五錢） 升麻（三分） 柴胡（三分） 陳皮（二分）",
    "reading_ko": null,
    "book": "bianzhenglu-辨證錄",
    "category": "저작-zhuzuo-著作"
  },
  {
    "id": 2446597,
    "original": "人有一時喉忽腫大而作痛，吐痰如涌，口渴求水，下喉少快，已而又熱，呼水，咽喉長成雙蛾，既大且赤，其形宛如雞冠，此喉痹之癥，即俗稱為纏喉風也。",
    "reading_ko": null,
    "book": "bianzhenglu-辨證錄",
    "category": "저작-zhuzuo-著作"
  },
  {
    "id": 4390672,
    "original": "雞腸草（一兩） 牡蠣粉（三分） 龍骨 麥門冬（去心焙） 白茯苓 桑螵蛸（各半兩）",
    "reading_ko": null,
    "book": "youyouxinshu-幼幼新書",
    "category": "저작-zhuzuo-著作"
  },
  {
    "id": 3982710,
    "original": "其不知之，故人人有異說，或有以《素》、《靈》解仲景之書者，或有以晉唐醫學，說仲景之書者，近世或有以名與數，解仲景之書者，或有取己之臆，辨仲景之書者，要之是又不知仲景真面目者也。",
    "reading_ko": null,
    "book": "yaozhengxubian-藥征續編",
    "category": "저작-zhuzuo-著作"
  }
]
```

## 출력
반드시 아래 JSON 형식으로만 응답:
```json
{
  translations: [
    {id: 숫자, ko: 번역문},
    ...
  ]
}
```
