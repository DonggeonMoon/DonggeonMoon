# 자바 네이밍

## 메서드

1. 메서드 이름에는 `소문자 캐멀 케이스`를 사용한다.
2. 메서드 이름은 영어를 사용하며, `하나의 동사나 전치사`만을 사용하거나 `동사 + 목적어`, `전치사 + 명사` 형태로 사용한다.
* 두 단어 이상의 메서드 이름은 전치사로 끝내지 않는다. 인수를 받는 메서드의 경우 전치사를 쓰면 좀 더 문장에 가까워지지만 올바르지 못한 전치사를 사용하거나 다른 개발자들에게 오해를 일으킬 수 있으므로 사용하지 않는다.
* boolean을 반환하는 메서드는 is로 시작하거나 3인칭 단수형 동사을 쓴다.
  * ex) isValid(), equals()
