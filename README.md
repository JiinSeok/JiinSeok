<img align="right" width="170" src="dev-jiin.png" alt="Jiin Seok — 노트북을 든 도트 캐릭터" />

<h2>
  Hi, I'm Jiin Seok from Korea 😽
</h2>

:fairy_woman: _a frontend & BFF developer with a knack for uncovering problems and weaving them into **clean & magical** solutions_ :fairy_woman:

And always on the lookout for great plugins :gear: and switches! :keyboard: Any favorites to share? <br>
**Feel free to reach me at** [**seokjiin1073@gmail.com**](mailto:seokjiin1073@gmail.com) <br>
JetBrains users and tactile switch lovers, you're especially welcome :white_heart: <br>

**Fun fact:** I used to be a QA engineer, and I still obsess over **seamless** user experiences!


### Summary of my skills:
- **Languages & Frameworks**

  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3776AB?style=flat-square&logo=TypeScript&logoColor=white"/>
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-FFE44A?style=flat-square&logo=JavaScript&logoColor=white"/>
  <img alt="React" src="https://img.shields.io/badge/React-58C4DC?style=flat-square&logo=React&logoColor=white"/>
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-181717?style=flat-square&logo=Next.js&logoColor=white"/>
  <img alt="Ruby on Rails" src="https://img.shields.io/badge/RubyOnRails-d30005?style=flat-square&logo=RubyOnRails&logoColor=white"/>  
  
  <br>
- **Tools**

  <img alt="WebStorm" src="https://img.shields.io/badge/WebStorm-007ACC?style=flat-square&logo=WebStorm&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white" />
  <img alt="Figma" src="https://img.shields.io/badge/Figma-FF7262?style=flat-square&logo=Figma&logoColor=white" />


### Currently working on:

- 🛠 **Developing**: Improving my Swift application
- 📖 **Learning**: Diving into Elixir!
- 🌍 **Exploring**: Accessibility (making sure digital information is accessible through every possible way)


:genie: _Excited to connect and craft **clean & magical** experiences together!_ :genie:

---

## BREAKING NEWS: iOS App is now available on the App Store!

Come here to get updates!

- https://tappytype.com
- https://instagram.com/tappytype
- https://apps.apple.com/us/app/tappytype/id6777860562


---

## BREAKING NEWS: npm package released! · npm 패키지 출시!

**FormKit React** — my React form library is finally public! <br>
**FormKit React** - React 폼 라이브러리가 드디어 공개되었습니다!

A take-home assignment that grew way out of hand — feedback very welcome! <br>
사전과제 하다 너무 발전해버린 케이스...! 많은 관심과 피드백 부탁드립니다!

- 📦 **npm**: https://www.npmjs.com/package/@jiin.seok/formkit-react
- ☁️ **github**: https://github.com/JiinSeok/formkit-react

```bash
npm i @jiin.seok/formkit-react
```

### Highlights · 특징
- Clean API with the **Compound Component Pattern** · **Compound Component Pattern**으로 깔끔한 API
- Auto **password toggle & match validation** · **비밀번호 토글 & 비밀번호 일치 검증** 자동 생성
- **Zod schema** support (optional) · **Zod 스키마** 지원 (선택사항)
- State management on **React Hook Form** · **React Hook Form** 기반 상태 관리
- Full **accessibility** with automatic ARIA · **접근성** 완벽 지원 (ARIA 자동 처리)
- Advanced **Select** component with Radix UI · **고급 Select** 컴포넌트 (Radix UI 활용)

### When it helps · 이럴 때 추천
- 😵‍💫 Tired of declaring ten useStates · useState 10개 선언하다 지칠 때
- 😭 Form validation giving you a headache · form validation 때문에 머리 아플 때
- 🔄 Sick of rebuilding the password toggle every time · 비밀번호 토글 버튼 매번 만들기 귀찮을 때
- ⏰ No time to learn a new library · 급해서 새 라이브러리 배울 시간 없을 때

### Automation · 자동화
```tsx
<FormKit.Input type="password" />        // auto toggle · 토글 자동 생성
<FormKit.Input name="confirmPassword" /> // auto match check · 비밀번호 일치 자동 검증
```

### Example · 사용 예시

```tsx
  <FormKit.Root formId="login" onSubmit={handleSubmit}>
    <FormKit.Field>
      <FormKit.Label>Email</FormKit.Label>
      <FormKit.Input name="email" type="email" required />
    </FormKit.Field>

    <FormKit.Field>
      <FormKit.Label>Password</FormKit.Label>
      <FormKit.Input name="password" type="password" required />
    </FormKit.Field>

    <FormKit.SubmitButton>Login</FormKit.SubmitButton>
  </FormKit.Root>
```
