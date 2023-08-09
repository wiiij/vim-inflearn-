# vim-inflearn-
vim은 텍스트 기반에 에디터면서 간단하지만 아직도 많이 쓰인다 파일을 편집하는 에디

vim을 실행하고 vim 하고 엔터를 치면 기본 화면이 나옴.

:q enter를 하면 vm에서 빠져나가진다.

자주 사용되는 옵션 ↓

-t tag : tag로 jump하여 에디터 시작

-o files... : 여러 파일을 split 모드로 열기

-R files... : read-only mode(읽기전용)로 열기 vim 안에 있는 윈도우 기능을 쪼개서 사용

-d files... : diff mode 개발적인 툴에서 사용되고 두 개의 파일을 diff한다면 두 텍스트 문서의 차이점을 보여주고 그걸 vim에서 띄워주고 하이라이트도 보기 좋게 보여준다

vim 실행이 되면 여러 모드 중 반드시 하나를 선택하게 되어있고 기본적으로 진입 했을 때의 모드가 있고 무언가를 누르면 어떤 모드로 진입하고 모드 간에 전환이 됨

*Normal mode : 커서 이동이 주된 모드로 vim 시작 시의 모드, 즉 기본 모드이다.

*Insert mode : 내용을 입력하고 싶을 때 들어감, i,a,o 등의 명령어를 통해 Insert mode가 되어 삽입이 가능해진다.

*Visual mode : Normal mode에서 전환 후, 커서를 움직이면 visual 블럭이 생김(마우스로 클릭하여 드래그 하는 것처럼 영역이 선택이 됨) 이 영역에서 오퍼레이션이 가능하다

Select mode : 선택 영역을 바로 수정(거의 쓰이지 않음)

*Command-line mode : ':','/','?','!' 으로 명령을 수행함 노멀 모드에서 자주 쓰인다.

Ex mode : 과거 Ex라는 툴이 있었음. 발전 하면서 sed(텍스트 기반으로 바꿔치기)라는 툴이 생김 이와 비슷하게 생긴 Ex라는 툴의 기능을 vim이 품고 있음 Ex모드로 전환하면 vim의 역할이 바뀜. (대체가 가능한 기능이 있어서 많이 쓰이지 않는 듯)

Terminal-job mode : Normal mode에서 :terminal 명령을 하면 vim 창에서 터미널이 실행됨. 편집을 하다 mode를 이용하면 상황마다 실행하는 것이 가능하다

 *은 거의 필수로 알아야 하며 이것만 알아도 크게 무리는 없을 것.
