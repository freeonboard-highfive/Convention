# 📄 Commit Message Convention

커밋 컨벤션은 **git 커밋 메세지**를 위한 컨벤션입니다. git 커밋을 이용해 **더 나은 로그 가독성, 리뷰 프로세스, 코드 유지 보수**를 할 수 있습니다.

<br/>

## 📚 Commit Message Structure

커밋 메세지는 **제목**만 작성합니다.

> [#이슈 번호] 타입 :  제목
>  
> [#3] feat: Add new feature 

<br/>

### Type

커밋 메세지가 **어떤 의도**를 가진 메세지인지 알립니다.
**태그와 제목**으로 구성되어 있고 사용법은 **태그: 제목**의 형태입니다. (`: 뒤에만 space가 있다 !`)

**e.g. [#5] feat: 추가 Infinity Scroll**

#### Tags

<table style="text-align : center;">
    <th>태그</th>
    <th>의도</th>
    <tr>
        <td style="color : red">feat</td>
        <td style="color : red">A new feature</td>
    <tr/>
    <tr>
        <td style="color : red">fix</td>
        <td style="color : red">A bug fix</td>
    </tr>
    <tr>
        <td style="color : red">style</td>
        <td style="color : red">Formatting, missing semi colons, etc; no code change</td>
    <tr/>
    <tr>
        <td style="color : red">refactor</td>
        <td style="color : red">Refactoring production code</td>
    </tr>
    <tr>
        <td style="color : red">docs</td>
        <td style="color : red">Changes to documentation</td>
    <tr/>
    <tr>
        <td style="color : red">test</td>
        <td style="color : red">Adding tests, refactoring test; no production code change</td>
    </tr>   
    <tr>  
        <td style="color : red">chore</td>
        <td style="color : red">Updating build tasks, package manager configs, etc; no production code change</td>
    </tr>
</table>

### Title

제목은 메세지의 **짧은 요약**입니다. 다음과 같은 규칙을 가집니다.

1. "고침", "추가", "변경" 등 **명령조**로 시작합니다. ( 영어의 경우 동사 원형 )
2. 총 글자는 **50자** 이내
3. 마지막에 **특수문자 삽입 X**
4. **개조식** 구문 ( 간결, 요점적인 서술 )

> Feat: 추가 Infinty Scroll 기능

<br/>

# Reference

#### 🔗 [Udacity Git Commit Message Style Guide](https://udacity.github.io/git-styleguide/)
