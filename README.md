기본 쓰기 및 서식 지정 구문
간단한 구문을 사용하여 GitHub에서 산문 및 코드에 대한 정교한 서식을 만듭니다.

누가 이 기능을 사용할 수 있나요?
Markdown은 GitHub 웹 인터페이스에서 사용할 수 있습니다.

이 문서의 내용
제목
제목을 만들려면 제목 텍스트 앞에 1~6개의 # 기호를 추가합니다. 사용하는 #의 수에 따라 제목의 계층 구조 수준과 글꼴 크기가 결정됩니다.

# A first-level heading
## A second-level heading
### A third-level heading
계층 구조 수준을 나타내기 위해 형식 크기와 시각적 가중치로 내림차순인 샘플 h1, h2, h3 헤더를 보여 주는 렌더링된 GitHub Markdown의 스크린샷

두 개 이상의 제목을 사용하는 경우 GitHub는 파일 헤더 내에서 을(를) 클릭하여 액세스할 수 있는 목차를 자동으로 생성합니다. 각 제목은 목차에 나열되며, 제목을 클릭하면 선택한 섹션으로 이동할 수 있습니다.

노출되는 목차에 대한 드롭다운 메뉴가 있는 추가 정보 파일의 스크린샷 목차 아이콘은 진한 주황색 윤곽선으로 표시됩니다.

텍스트 스타일 지정
주석 필드 및 .md 파일에서 굵게, 기울임꼴 또는 취소선 텍스트로 강조를 나타낼 수 있습니다.

스타일	구문	단축키	예시	출력
굵게	** ** 또는 __ __	Command+B(Mac) 또는 Ctrl+B(Windows/Linux)	**This is bold text**	굵게 표시된 텍스트
이탤릭체	* * 또는 _ _     	Command+I(Mac) 또는 Ctrl+I(Windows/Linux)	_This text is italicized_	기울임꼴로 표시된 텍스트
취소선	~~ ~~ 또는 ~ ~	None	~~This was mistaken text~~	실수하여 취소된 텍스트
굵게 및 중첩된 기울임꼴	** ** 및 _ _	None	**This text is _extremely_ important**	매우 중요한 텍스트
모든 굵게 및 기울임꼴	*** ***	None	***All this text is important***	모든 텍스트가 중요
아래 첨자	<sub> </sub>	None	This is a <sub>subscript</sub> text	아래 첨자 텍스트입니다.
위 첨자	<sup> </sup>	None	This is a <sup>superscript</sup> text	위 첨자 텍스트입니다.
밑줄	<ins> </ins>	None	This is an <ins>underlined</ins> text	밑줄이 그어진 텍스트
텍스트 인용
>를 사용하여 텍스트를 인용할 수 있습니다.

Text that is not a quote

> Text that is a quote
따옴표 붙은 텍스트는 왼쪽에 세로선으로 들여쓰기되고 회색 형식으로 표시됩니다.

일반 텍스트와 따옴표 붙은 텍스트의 차이를 보여 주는 렌더링된 GitHub Markdown의 스크린샷

참고 항목

대화를 볼 때 텍스트를 강조 표시한 다음 R을 입력하면 주석의 텍스트를 자동으로 인용할 수 있습니다. 을(를) 클릭하고 회신 인용을 클릭하면 전체 주석을 인용할 수 있습니다. 단축키에 대한 자세한 내용은 단축키을(를) 참조하세요.

인용 코드
단일 백틱을 사용하여 문장 내에서 코드 또는 명령을 표시할 수 있습니다. 백틱 내의 텍스트는 서식이 지정되지 않습니다. Command+E(Mac) 또는 Ctrl+E(Windows/Linux) 단축키를 눌러 Markdown 줄 안에 코드 블록에 대한 백틱을 삽입할 수도 있습니다.

Use `git status` to list all new or modified files that haven't yet been committed.
백틱으로 둘러싸인 문자가 연한 회색으로 강조 표시된 고정 너비 서체로 표시되는 것을 보여 주는 렌더링된 GitHub Markdown의 스크린샷

고유한 블록 안으로 코드 또는 텍스트의 서식을 지정하려면 삼중 백틱을 사용합니다.

Some basic Git commands are:
```
git status
git add
git commit
```
구문 강조 표시 없이 간단한 코드 블록을 보여 주는 렌더링된 GitHub Markdown의 스크린샷

자세한 내용은 코드 블록 만들기 및 강조 표시을(를) 참조하세요.

코드 조각과 테이블을 자주 편집하는 경우 GitHub의 모든 주석 필드에서 고정 너비 글꼴을 사용하도록 설정하면 도움이 될 수 있습니다. 자세한 내용은 GitHub에서의 쓰기 및 서식 지정 정보을(를) 참조하세요.

지원되는 색 모델
이슈, 끌어오기 요청 및 토론에서 백틱을 사용하여 문장 내의 색을 나타낼 수 있습니다. 백틱 내에서 지원되는 색 모델은 색의 시각화를 표시합니다.

The background color is `#ffffff` for light mode and `#000000` for dark mode.
백틱 내의 HEX 값이 작은 흰색과 검은색의 원을 만드는 방법을 보여 주는 렌더링된 GitHub Markdown의 스크린샷

현재 지원되는 색 모델은 다음과 같습니다.

색	구문	예시	출력
HEX	`#RRGGBB`	`#0969DA`	HEX 값 #0969DA 파란색 원으로 표시되는 방법을 보여 주는 렌더링된 GitHub Markdown의 스크린샷.
RGB	`rgb(R,G,B)`	`rgb(9, 105, 218)`	RGB 값 9, 105, 218이 파란색 원으로 표시되는 방법을 보여 주는 렌더링된 GitHub Markdown의 스크린샷.
HSL	`hsl(H,S,L)`	`hsl(212, 92%, 45%)`	HSL 값 212, 92%, 45%가 파란색 원으로 표시되는 방법을 보여 주는 렌더링된 GitHub Markdown의 스크린샷.
참고 항목

지원되는 색 모델에서 백틱 내에는 선행 또는 후행 공백이 있을 수 없습니다.
색 시각화는 이슈, 끌어오기 요청 및 토론에서만 지원됩니다.
링크
링크 텍스트를 대괄호 [ ]로 묶은 다음 URL을 괄호 ( )로 묶어 인라인 링크를 만들 수 있습니다. 단축키 Command+K를 사용하여 링크를 만들 수도 있습니다. 텍스트를 선택한 경우 클립보드의 URL을 붙여넣어 선택 영역에서 링크를 자동으로 만들 수 있습니다.

텍스트를 강조 표시하고 Command+V를 사용하여 Markdown 하이퍼링크를 만들 수도 있습니다. 단축키인 Command+Shift+V를 사용하면 텍스트를 링크로 전환할 수 있습니다.

This site was built using [GitHub Pages](https://pages.github.com/).

대괄호 안의 텍스트인 "GitHub Pages"가 파란색 하이퍼링크로 표시되는 방법을 보여 주는 렌더링된 GitHub Markdown의 스크린샷.

참고 항목

GitHub는 주석에 유효한 URL이 작성되면 자동으로 링크를 만듭니다. 자세한 내용은 자동 링크된 참조 및 URL을(를) 참조하세요.

섹션 링크
제목이 있는 모든 섹션에 직접 연결할 수 있습니다. 렌더링된 파일에서 자동으로 생성된 앵커를 보려면 섹션 제목 위로 마우스를 가져가  아이콘을 표시하고 아이콘을 클릭하여 브라우저에 앵커를 표시합니다.

리포지토리의 추가 정보 스크린샷. 섹션 제목 왼쪽에 링크 아이콘이 진한 주황색 윤곽선으로 표시되어 있습니다.

편집 중인 파일에서 제목에 대한 앵커를 결정해야 하는 경우 다음 기본 규칙을 사용할 수 있습니다.

문자는 소문자로 변환됩니다.
스페이스는 하이픈(-)으로 바뀝니다. 다른 공백 또는 문장 부호 문자는 모두 제거됩니다.
선행 및 후행 공백은 제거됩니다.
마크업 서식이 제거되고 내용만 남습니다(예: _italics_는 italics가 됩니다).
제목에 대해 자동으로 생성된 앵커가 동일한 문서의 이전 앵커와 동일한 경우 하이픈과 자동 증가 정수를 추가하여 고유 식별자가 생성됩니다.
URI 조각의 요구 사항에 대한 자세한 내용은 RFC 3986: URI(Uniform Resource Identifier): 제네릭 구문, 섹션 3.5를 참조하세요.

아래 코드 블록은 렌더링된 콘텐츠의 제목에서 앵커를 생성하는 데 사용되는 기본 규칙을 보여 줍니다.

# Example headings

## Sample Section

## This'll be a _Helpful_ Section About the Greek Letter Θ!
A heading containing characters not allowed in fragments, UTF-8 characters, two consecutive spaces between the first and second words, and formatting.

## This heading is not unique in the file

TEXT 1

## This heading is not unique in the file

TEXT 2

# Links to the example headings above

Link to the sample section: [Link Text](#sample-section).

Link to the helpful section: [Link Text](#thisll-be-a-helpful-section-about-the-greek-letter-Θ).

Link to the first non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file).

Link to the second non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file-1).
참고 항목

제목을 편집하거나 "동일한" 앵커를 사용하여 제목 순서를 변경하는 경우 앵커가 변경될 때 해당 제목의 링크도 업데이트해야 합니다.

상대 링크
렌더링된 파일에서 상대 링크 및 이미지 경로를 정의하여 판독기에서 리포지토리의 다른 파일로 이동할 수 있습니다.

상대 링크는 현재 파일을 기준으로 하는 링크입니다. 예를 들어 리포지토리의 루트에 추가 정보 파일이 있고 _docs/CONTRIBUTING.md_에 다른 파일이 있는 경우 추가 정보의 _CONTRIBUTING.md_에 대한 상대 링크는 다음과 같습니다.

[Contribution guidelines for this project](docs/CONTRIBUTING.md)
GitHub는 현재 위치한 분기에 따라 상대 링크 또는 이미지 경로를 자동으로 변환하므로 링크 또는 경로는 항상 작동합니다. 링크의 경로는 현재 파일을 기준으로 합니다. / 시작 링크는 리포지토리 루트를 기준으로 합니다. ./ 및 ../와 같은 모든 상대 링크 피연산자를 사용할 수 있습니다.

링크 텍스트는 한 줄이어야 합니다. 아래 예는 작동하지 않습니다.

[Contribution
guidelines for this project](docs/CONTRIBUTING.md)
상대 링크는 리포지토리를 복제하는 사용자가 사용하기 더 쉽습니다. 절대 링크는 리포지토리의 복제본에서 작동하지 않을 수 있습니다. 상대 링크를 사용하여 리포지토리 내의 다른 파일을 참조하는 것이 좋습니다.

사용자 지정 앵커
표준 HTML 앵커 태그(<a name="unique-anchor-name"></a>)를 사용하여 문서의 모든 위치에 대한 탐색 앵커 지점을 만들 수 있습니다. 모호한 참조를 피하려면 name 특성 값에 접두사를 추가하는 등 앵커 태그에 고유한 명명 체계를 사용합니다.

참고 항목

사용자 지정 앵커는 문서 개요/목차에 포함되지 않습니다.

앵커에 지정한 name 특성의 값을 사용하여 사용자 지정 앵커에 연결할 수 있습니다. 구문은 제목에 대해 자동으로 생성되는 앵커에 연결할 때와 정확히 동일합니다.

예시:

# Section Heading

Some body text of this section.

<a name="my-custom-anchor-point"></a>
Some text I want to provide a direct link to, but which doesn't have its own heading.

(… more content…)

[A link to that custom anchor](#my-custom-anchor-point)
팁

사용자 지정 앵커는 자동 제목 링크의 자동 이름 지정 및 번호 매기기 동작으로 간주되지 않습니다.

줄 바꿈
문제, 끌어오기 요청 또는 토론을 리포지토리에 작성하는 경우 GitHub는 자동으로 줄 바꿈을 렌더링합니다.

This example
Will span two lines
그러나 .md 파일에서 작성하는 경우 위의 예제는 줄 바꿈 없이 한 줄에 렌더링됩니다. .md 파일에서 줄 바꿈을 만들려면 다음 중 하나를 포함해야 합니다.

첫 번째 줄 끝에 공백 두 개를 포함합니다.

This example  
Will span two lines
첫 번째 줄 끝에 백슬래시를 포함합니다.

This example\
Will span two lines
첫 번째 줄 끝에 HTML 단일 줄 바꿈 태그를 포함합니다.

This example<br/>
Will span two lines
두 줄 사이에 빈 줄을 넣으면 .md 파일과 문제, 끌어오기 요청, 토론에서 사용되는 Markdown이 모두 빈 줄로 구분되어 두 줄로 렌더링합니다.

This example

Will have a blank line separating both lines
이미지
!를 추가하고 [ ]에 대체 텍스트를 넣어 이미지를 표시할 수 있습니다. 대체 텍스트는 이미지의 정보와 동일한 짧은 텍스트입니다. 그런 다음 이미지에 대한 링크를 괄호 ()에 넣습니다.

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

Markdown에 추가된 이미지를 보여 주는 GitHub 문제에 대한 댓글의 스크린샷으로, 촉수를 들고 웃고 있는 옥토캣의 모습.

GitHub는 이슈, 끌어오기 요청, 토론, 주석, .md 파일에 이미지를 포함하는 기능을 지원합니다. 리포지토리에 있는 이미지를 표시하거나, 온라인 이미지에 대한 링크를 추가하거나, 이미지를 업로드할 수 있습니다. 자세한 내용은 자산 업로드를 참조하세요.

참고 항목

리포지토리에 있는 이미지를 표시하려면 절대 링크 대신 상대 링크를 사용해야 합니다.

다음은 상대 링크를 사용하여 이미지를 표시하는 몇 가지 예입니다.

컨텍스트	상대 링크
동일한 분기의 .md 파일에서	/assets/images/electrocat.png
다른 분기의 .md 파일에서	/../main/assets/images/electrocat.png
리포지토리의 이슈, 끌어오기 요청, 주석에서	../blob/main/assets/images/electrocat.png?raw=true
다른 리포지토리의 .md 파일에서	/../../../../github/docs/blob/main/assets/images/electrocat.png
다른 리포지토리의 이슈, 끌어오기 요청, 주석에서	../../../github/docs/blob/main/assets/images/electrocat.png?raw=true
참고 항목

위 표에 표시된 두 개의 마지막 상대 링크는 뷰어에게 해당 이미지가 포함된 프라이빗 리포지토리에 대한 최소 읽기 권한이 있는 경우에만 프라이빗 리포지토리의 이미지에 대해 작동합니다.

자세한 내용은 상대 링크를 참조하세요.

Picture 요소
<picture> HTML 요소가 지원됩니다.

목록
하나 이상의 텍스트 행 앞에 -, *, 또는 +을(를) 입력하여 순서가 지정되지 않은 목록을 만들 수 있습니다.

- George Washington
* John Adams
+ Thomas Jefferson
처음 세 명의 미국 대통령의 이름에 대한 글머리 기호 목록을 보여 주는 렌더링된 GitHub Markdown의 스크린샷.

목록의 순서를 지정하려면 각 줄 앞에 숫자를 입력합니다.

1. James Madison
2. James Monroe
3. John Quincy Adams
네 번째, 다섯 번째, 여섯 번째 미국 대통령의 이름 번호가 매겨진 목록을 보여 주는 렌더링된 GitHub Markdown의 스크린샷.

중첩된 목록
하나 이상의 목록 항목을 다른 항목 아래에 포함하여 중첩된 목록을 만들 수 있습니다.

GitHub의 웹 편집기 또는 Visual Studio Code와 같은 고정 폭 글꼴을 사용하는 텍스트 편집기를 사용하여 중첩 목록을 만들기 위해 목록을 시각적으로 정렬할 수 있습니다. 목록 표식 문자(- 또는 *)가 위 항목에 있는 텍스트의 첫 번째 문자 바로 아래에 올 때까지 중첩 목록 항목 앞에 공백 문자를 입력합니다.

1. First list item
   - First nested list item
     - Second nested list item
참고 항목

웹 기반 편집기에서 원하는 줄을 먼저 강조 표시한 다음 Tab 또는 Shift+Tab을 각각 사용하여 하나 이상의 텍스트 줄을 들여쓰거나 내어쓸 수 있습니다.

중첩된 번호 매기기 줄과 글머리 기호 들여쓰기를 보여 주는 Visual Studio Code의 Markdown 스크린샷

두 개의 서로 다른 중첩 수준에서 중첩된 글머리 기호 뒤에 번호가 매겨진 항목을 보여 주는 렌더링된 GitHub Markdown의 스크린샷

고정 폭 글꼴을 사용하지 않는 GitHub의 주석 편집기에서 중첩된 목록을 만들려면 중첩된 목록 바로 위에 있는 목록 항목을 확인하고 항목의 내용 앞에 표시되는 문자 수를 계산할 수 있습니다. 그런 다음 중첩된 목록 항목 앞에 해당 수만큼의 공백 문자를 입력합니다.

이 예제에서는 First list item 앞에 5개 문자(100. )가 있으므로 중첩된 목록 항목을 최소 5개 공백으로 들여써서 목록 항목 100. First list item 아래에 중첩된 목록 항목을 추가할 수 있습니다.

100. First list item
     - First nested list item
번호 100 앞에 나열된 목록 항목과 오른쪽에 한 단계 중첩된 글머리 기호 항목이 앞에 표시된 렌더링된 GitHub Markdown의 스크린샷

동일한 방법을 사용하여 여러 수준의 중첩된 목록을 만들 수 있습니다. 예를 들어 첫 번째 중첩된 목록 항목에는 중첩된 목록 내용 First nested list item 앞에 일곱 자의 문자(␣␣␣␣␣-␣)가 있으므로, 두 번째 중첩된 목록 항목은 첫 번째 목록 항목보다 두 자 이상 더 들여써야 하며, 이 경우에는 최소 9 개의 공백이 필요합니다.

100. First list item
     - First nested list item
       - Second nested list item
번호 100 앞에 번호가 매겨진 항목과 두 단계 중첩된 글머리 기호가 앞에 표시된 렌더링된 GitHub Markdown의 스크린샷

더 많은 예제는 GitHub Flavored Markdown 사양을 참조하세요.

작업 목록
작업 목록을 만들려면 하이픈과 공백 뒤에 [ ]이 오는 목록 항목의 접두사를 설정합니다. 작업을 완료로 표시하려면 [x]를 사용합니다.

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
렌더링된 버전의 markdown을 보여 주는 스크린샷. 문제에 대한 참조가 문제 제목으로 렌더링됩니다.

작업 목록 항목 설명이 괄호로 시작하는 경우 \로 이스케이프해야 합니다.

- [ ] \(Optional) Open a followup issue

자세한 내용은 작업 목록 정보을(를) 참조하세요.

사람과 팀 멘션
사용자 이름 또는 팀 이름과 함께 @을 입력하여 GitHub에서 개인 또는 팀을 멘션할 수 있습니다. 그러면 알림이 트리거되고 해당 사용자의 주의를 대화에 집중시킬 수 있습니다. 또한 사용자 이름 또는 팀 이름을 멘션하는 메모를 편집하는 경우에도 해당 사용자는 알림을 받게 됩니다. 알림에 대한 자세한 내용은 알림 정보을(를) 참조하세요.

참고 항목

리포지토리에 대한 읽기 권한이 있는 경우에만 멘션에 대한 알림을 받으며 리포지토리를 조직에서 소유한 경우 해당 사용자는 조직의 구성원이 됩니다.

@github/support What do you think about these updates?

팀 멘션 "@github/support"을(를) 굵고 클릭 가능한 텍스트로 렌더링하는 방법을 보여 주는 렌더링된 GitHub Markdown의 스크린샷.

상위 팀을 멘션할 경우 하위 팀의 구성원도 알림을 수신하므로, 여러 사용자 그룹과의 통신이 간소화됩니다. 자세한 내용은 팀 정보을(를) 참조하세요.

@ 기호를 입력하면 프로젝트에 사용자 또는 팀 목록이 표시됩니다. 입력할 때 목록이 필터링되므로 찾고 있는 사용자나 팀의 이름을 찾았으면 화살표 키를 사용하여 선택하고 Tab 또는 Enter 키를 눌러 이름을 완성할 수 있습니다. 팀의 경우 @organization/team-name을 입력하면 해당 팀의 모든 구성원이 대화를 구독하게 됩니다.

자동 완성 결과는 리포지토리 협력자 및 스레드의 다른 참가자로 제한됩니다.

이슈 및 끌어오기 요청 참조
#을 입력하여 리포지토리 내에서 제안된 이슈 및 끌어오기 요청 목록을 표시할 수 있습니다. 이슈, 끌어오기 요청 번호 또는 제목을 입력하여 목록을 필터링한 다음, Tab 또는 Enter 키를 눌러 강조 표시된 결과를 완성합니다.

자세한 내용은 자동 링크된 참조 및 URL을(를) 참조하세요.

외부 리소스 참조
리포지토리에 사용자 지정 자동 링크 참조가 구성된 경우 JIRA 문제 또는 Zendesk 티켓과 같은 외부 리소스에 대한 참조가 단축된 링크로 변환됩니다. 리포지토리에서 사용할 수 있는 자동 링크를 알아보려면 리포지토리에 대한 관리자 권한이 있는 사람에게 문의하세요. 자세한 내용은 외부 리소스를 참조하도록 자동 링크 구성을(를) 참조하세요.

자산 업로드 중
끌어서 놓기, 파일 브라우저에서 선택, 붙여넣기 등을 통해 이미지와 같은 자산을 업로드할 수 있습니다. 리포지토리의 이슈, 끌어오기 요청, 주석, .md 파일에 자산을 업로드할 수 있습니다.

이모지 사용
:EMOJICODE:, 콜론, 이모지 이름 순으로 입력하여 글에 이모지를 추가할 수 있습니다.

@octocat :+1: This PR looks great - it's ready to merge! :shipit:

+1 및 shipit에 대한 이모지 코드가 이모지로 시각적으로 렌더링되는 방법을 보여 주는 렌더링된 GitHub Markdown의 스크린샷.

:을 입력하면 제안된 이모지 목록이 표시됩니다. 입력할 때 목록이 필터링되므로 원하는 이모지를 찾았으면 Tab 또는 Enter 키를 눌러 강조 표시된 결과를 완성합니다.

사용 가능한 이모지 및 코드의 전체 목록을 보려면 Emoji-Cheat-Sheet를 확인하세요.

단락
텍스트 줄 사이에 빈 줄을 두어 새 단락을 만들 수 있습니다.

각주
이 대괄호 구문을 사용하여 콘텐츠에 각주를 추가할 수 있습니다.

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
각주가 다음과 같이 렌더링됩니다.

각주를 나타내는 데 사용되는 위 첨자 번호와 메모 내의 선택적 줄 바꿈을 보여 주는 렌더링된 Markdown의 스크린샷.

참고 항목

Markdown에서 각주의 위치는 각주가 렌더링될 위치에 영향을 주지 않습니다. 각주에 대한 참조 바로 뒤에 각주를 작성할 수 있으며, 각주는 여전히 Markdown의 하단에 렌더링됩니다. 각주는 wiki에서 지원되지 않습니다.

경고
경고는 중요한 정보를 강조하는 데 사용할 수 있는 blockquote 구문을 기반으로 한 Markdown 확장입니다. GitHub에서는 콘텐츠의 중요도를 나타내기 위해 고유한 색과 아이콘으로 표시됩니다.

경고는 사용자 성공에 중요한 경우에만 사용하고, 판독기 오버로드를 방지하기 위해 문서당 하나 또는 두 개로 제한합니다. 또한 경고를 연속적으로 배치하지 않아야 합니다. 경고는 다른 요소 내에 중첩될 수 없습니다.

경고를 추가하려면 경고 유형을 지정하는 특수 blockquote 줄을 사용하고, 그 다음에는 표준 blockquote의 경고 정보를 사용합니다. 5가지 유형의 경고를 사용할 수 있습니다.

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
렌더링된 경고는 다음과 같습니다.

참고, 팁, 중요, 경고, 주의가 서로 다른 색의 텍스트와 아이콘으로 렌더링되는 방식을 보여 주는 렌더링된 Markdown 경고의 스크린샷.

주석이 있는 콘텐츠 숨기기
HTML 주석에 콘텐츠를 배치하여 렌더링된 Markdown에서 콘텐츠를 숨기도록 GitHub에 지시할 수 있습니다.

<!-- This content will not appear in the rendered Markdown -->
Markdown 서식 무시
Markdown 문자 앞에 \를 사용하여 Markdown 형식을 무시(또는 이스케이프)하도록 GitHub에 지시할 수 있습니다.

Let's rename \*our-new-project\* to \*our-old-project\*.

백슬래시가 별표를 기울집으로 변환하지 못하게 하는 방법을 보여 주는 렌더링된 GitHub Markdown의 스크린샷.

백슬래시에 대한 자세한 내용은 Daring Fireball의 Markdown 구문을 참조하세요.

참고 항목

Markdown 서식은 문제 또는 끌어오기 요청의 제목에서 무시되지 않습니다.

Markdown 렌더링 사용 안 함
Markdown 파일을 볼 때 파일 위쪽의 Code를 클릭하여 Markdown 렌더링을 사용하지 않도록 설정하고 대신 파일의 원본을 볼 수 있습니다.

파일과 상호 작용하기 위한 옵션을 보여 주는 리포지토리의 Markdown 파일 스크린샷 "코드"라는 레이블이 지정된 버튼은 진한 주황색으로 표시됩니다.

Markdown 렌더링을 사용하지 않도록 설정하면 렌더링된 Markdown 파일을 볼 때 사용할 수 없는 줄 연결과 같은 원본 보기 기능을 사용할 수 있습니다.

추가 참고 자료
GitHub Flavored Markdown 사양
GitHub에서의 쓰기 및 서식 지정 정보
고급 서식 지정 작업
GitHub에서 쓰기 위한 빠른 시작
