* 다른 PC에서 github에 등록된 나의 repository를 가져오기
1) 해당 repository의 settings에 들어가서 제일 밑 하단에 Danger Zone 영역의
    "Change repository visibility" 설정을 공개로 전환한다.
2) sts에서 remote git을 가져온다. 로그인이 안될 경우 URI를 https://freeksw%40nate.com@github.com/seonwoo-kim/springboot.git 으로 해볼것
3) 연결된 후에는 Remotes - origin 밑에 fetch, push 아무거나 선택 후 마우스 우측 버튼의 "Change Credentials"를 선택하여 토큰 정보를 넣는다.
4) https://github.com/settings/tokens?type=beta 들어가서 "swkim-token" 선택하고, Regenerate token 선택하여 나온 토큰 값을 넣어준다.
   (이걸 안하고 아이디, 패스워드만 넣을 경우 로그인 되지 않음)