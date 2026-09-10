# 💰 대출상환계산기 (Loan Repayment Calculator)

## 📖 프로젝트 소개
사용자가 대출 금액, 대출 금리, 상환 기간 등을 입력하면 매월 상환해야 할 원금과 이자를 자동으로 계산해 주는 웹 애플리케이션입니다. 
다양한 상환 방식(원리금균등, 원금균등, 만기일시상환)을 지원하여 사용자가 더 명확한 재무 계획을 세울 수 있도록 돕습니다.

## ✨ 주요 기능
- **3가지 상환 방식 지원**: 
  - 원리금균등상환
  - 원금균등상환
  - 만기일시상환
- **실시간 계산 결과 제공**: 총 이자, 총 상환 금액, 1회차 상환 금액 등 요약 정보 제공
- **월별 상환 일정표**: 회차별 납입 원금, 납입 이자, 월 상환금, 대출 잔금을 표(Table) 형태로 시각화
- **반응형 디자인**: PC, 태블릿, 모바일 등 다양한 기기에서 최적화된 화면 제공

## 🛠 기술 스택
> 💡 *프로젝트에 맞게 사용하신 기술로 수정해 주세요.*
- **Frontend**: HTML5, CSS3, Vanilla JavaScript (또는 React, Vue 등)
- **Styling**: Tailwind CSS / Styled Components
- **Deployment**: Vercel / GitHub Pages

## 🚀 설치 및 실행 방법

1. 저장소를 클론합니다.
   ```bash
   git clone https://github.com/본인계정/loan-calculator.git
   ```

2. 프로젝트 폴더로 이동합니다.
   ```bash
   cd loan-calculator
   ```

3. 프로젝트를 실행합니다.
   - **정적 웹사이트인 경우**: `index.html` 파일을 웹 브라우저로 엽니다.
   - **Node.js/React 기반인 경우**:
     ```bash
     npm install
     npm start
     ```

## 💡 사용 방법
1. **대출 금액**을 입력합니다. (예: 100,000,000)
2. **연 이자율(%)**을 입력합니다. (예: 4.5)
3. **대출 기간**을 입력합니다. (예: 24개월)
4. 원하는 **상환 방식**을 선택합니다.
5. **'계산하기'** 버튼을 클릭하면 하단에 총 상환 금액과 월별 상환 내역표가 출력됩니다.

## 📸 스크린샷
<!-- 여기에 실제 프로젝트의 스크린샷 이미지 경로를 넣어주세요 -->
![스크린샷 예시](https://via.placeholder.com/800x450.png?text=Loan+Calculator+Screenshot+Here)

## 🤝 기여 방법
1. 이 저장소를 Fork 합니다.
2. 새로운 Branch를 생성합니다. (`git checkout -b feature/새로운기능`)
3. 변경 사항을 Commit 합니다. (`git commit -m 'Add 새로운기능'`)
4. Branch에 Push 합니다. (`git push origin feature/새로운기능`)
5. Pull Request를 생성합니다.

## 📝 라이선스
이 프로젝트는 [MIT 라이선스](LICENSE)를 따릅니다.
