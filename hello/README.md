# 플로팅 액션버튼
```
binding.fab.setOnClickListener { view ->
            Snackbar.make(view, "Replace with your own action", Snackbar.LENGTH_LONG)
                    .setAction("Action", null).show()
        }
```
setOnClickListener  버튼을 클릭하면 Snackbar를 만들어서 Replace with your own action를 넣어고 보여줘라

# AndroidMainfests.xml = 자바의 xml과 같은 역할

## @로 시작하는 것들은 어딘가보루터 연결되어 있는것
## text:"@string/"으로 시작하는 것들은 strings에서 다국어 지원 연결을 할 수 있다.
## 언어별로 문자가 바뀌게 할 수 있다.