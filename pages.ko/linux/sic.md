# sic

> Simple IRC 클라이언트.
> suckless 도구의 일부.
> 더 많은 정보: <https://manned.org/sic>.

- 기본 호스트(irc.ofct.net)에 `$USER` 환경 변수에 설정된 닉네임으로 연결:

`sic`

- 주어진 호스트에 주어진 닉네임으로 연결:

`sic -h {{호스트}} -n {{닉네임}}`

- 주어진 호스트에 주어진 닉네임과 비밀번호로 연결:

`sic -h {{호스트}} -n {{닉네임}} -k {{비밀번호}}`

- 채널 참여:

`:j #{{채널}}<Enter>`

- 채널이나 사용자에게 메시지 전송:

`:m #{{채널|사용자}}<Enter>`

- 기본 채널이나 사용자 설정:

`:s #{{채널|사용자}}<Enter>`
