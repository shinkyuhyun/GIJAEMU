<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
<title>중간고사 범위 퀴즈</title>
<style>
* { box-sizing: border-box; -webkit-tap-highlight-color: transparent; }

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
  background: #f1f5f9;
  margin: 0;
  padding: 0;
  -webkit-text-size-adjust: 100%;
}

.container {
  max-width: 900px;
  margin: auto;
  padding: 16px;
}

.header {
  background: #fff;
  border-radius: 18px;
  padding: 20px;
  margin-bottom: 16px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}

.header h1 {
  font-size: clamp(18px, 5vw, 26px);
  margin: 0 0 8px 0;
}

.header p {
  font-size: clamp(13px, 3.5vw, 15px);
  margin: 0;
  color: #64748b;
}

.card {
  background: #fff;
  border-radius: 18px;
  padding: 18px;
  margin-bottom: 14px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}

.card strong {
  font-size: clamp(13px, 3.8vw, 15px);
  line-height: 1.6;
  display: block;
  margin-bottom: 10px;
}

.option {
  display: flex;
  gap: 10px;
  width: 100%;
  padding: 13px 14px;
  margin: 6px 0;
  border-radius: 12px;
  border: 1.5px solid #ddd;
  background: #fff;
  cursor: pointer;
  text-align: left;
  font-size: clamp(13px, 3.5vw, 14px);
  line-height: 1.5;
  transition: background 0.15s, border-color 0.15s, transform 0.1s;
  word-break: keep-all;
  -webkit-appearance: none;
  appearance: none;
}

.option:hover:not(:disabled) {
  background: #f8fafc;
  border-color: #94a3b8;
  transform: translateY(-1px);
}

.option:active:not(:disabled) {
  transform: scale(0.98);
}

.option.selected { background: #e2e8f0; border-color: #000; }
.option.correct  { background: #dcfce7; border-color: #22c55e; }
.option.wrong    { background: #fee2e2; border-color: #ef4444; }

.badge {
  display: inline-block;
  padding: 4px 10px;
  border-radius: 999px;
  font-size: 12px;
  font-weight: bold;
  margin: 6px 0 8px;
}
.ok { background: #dcfce7; color: #15803d; }
.no { background: #fee2e2; color: #b91c1c; }

.result {
  background: #0f172a;
  color: #fff;
  padding: 16px;
  border-radius: 14px;
  margin-bottom: 16px;
  display: none;
  font-size: clamp(14px, 4vw, 16px);
}

.answer-text {
  font-size: clamp(12px, 3.2vw, 13px);
  color: #374151;
  margin-top: 8px;
  line-height: 1.5;
}

/* 서술형 */
.card h2 {
  font-size: clamp(15px, 4.5vw, 18px);
  margin: 0 0 12px 0;
}

.card p {
  font-size: clamp(13px, 3.5vw, 14px);
  line-height: 1.6;
  margin: 12px 0 4px;
  word-break: keep-all;
}

textarea {
  width: 100%;
  height: 90px;
  margin-top: 6px;
  border-radius: 10px;
  border: 1px solid #ccc;
  padding: 10px;
  font-size: clamp(13px, 3.5vw, 14px);
  font-family: inherit;
  resize: vertical;
  -webkit-appearance: none;
}

/* 버튼 */
.btn-row {
  display: flex;
  gap: 10px;
  margin-top: 10px;
}

button.main {
  flex: 1;
  padding: 15px;
  border: none;
  border-radius: 12px;
  background: #0f172a;
  color: #fff;
  font-weight: bold;
  font-size: clamp(14px, 4vw, 15px);
  cursor: pointer;
  transition: background 0.2s, transform 0.15s, box-shadow 0.2s;
  -webkit-appearance: none;
  appearance: none;
}

button.main:hover {
  background: #1e3a5f;
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(15, 23, 42, 0.3);
}

button.main:active {
  transform: scale(0.97);
  box-shadow: none;
}

button.main.reset-btn {
  background: #475569;
}

button.main.reset-btn:hover {
  background: #64748b;
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(71, 85, 105, 0.3);
}

/* 이미지 */
.card img {
  max-width: 100%;
  border-radius: 10px;
  height: auto;
}
</style>
</head>
<body>
<div class="container">

  <div class="header">
    <h1>중간고사 범위 퀴즈</h1>
    <p>복수선택 문제는 전부 맞춰야 정답 처리됩니다.</p>
  </div>

  <div id="result" class="result"></div>
  <div id="quiz"></div>

  <div class="card">
    <h2>서술형</h2>
    <p>1. 앞으로 1년 동안 5%의 연간이자율이, 이후 2년 동안에는 6%의 연간이자율이 적용되는 경우 주어진 현금흐름의 현가를 구하라</p>
    <textarea id="w1"></textarea>
    <div id="wr1"></div>

    <p>2. 영업현금흐름이 자금조달활동에 따른 이자비용의 지급 여부에 영향을 받지 않는 이유를 설명하라</p>
    <textarea id="w2"></textarea>
    <div id="wr2"></div>
  </div>

  <div class="btn-row">
    <button class="main" onclick="submitQuiz()">제출하기</button>
    <button class="main reset-btn" onclick="resetQuiz()">다시 풀기</button>
  </div>

</div>

<script>
const quizData=[
{
 id:1,
 q:"주식 a의 수익률의 기댓값과 표준편차가 각각 9%와 20%이고, 주식 b의 수익률의 기댓값과 표준편차가 각각 5%와 10%이다. a와 b에 분산투자하는 포트폴리오 c의 평균과 분산에 관한 주장 중 맞는 것을 모두 고르시오 (단 공매도가 가능하며, 두 주식의 움직임은 서로 독립이다)",
 options:[
  "포트폴리오 c의 기대수익률은 29%가 될 수 있다.",
  "포트폴리오 c의 기대수익률은 0%가 될 수 있다.",
  "포트폴리오 c의 기대수익률은 -5%가 될 수 있다.",
  "포트폴리오 c의 분산은 0이 될 수 있다."
 ],
 answer:[0,1,2]
},
{
 id:2,
 q:"다음 설명 중 옳은 것을 모두 고르시오",
 options:[
  "분산투자의 효과는 투자자산들 사이의 관계성과 무관하게 결정된다.",
  "시장 이자율이 상승하면 채권가격은 하락한다.",
  "채권의 가격은 액면가 보다는 항상 낮아야한다.",
  "현금흐름의 위험이 작을수록 더 작은 할인율로 현재가치를 구해야한다."
 ],
 answer:[1,3]
},
{
 id:3,
 q:"기대효용가설과 마코위츠의 포트폴리오이론에 근거하여 다음 중 틀린 것은?",
 options:[
  "동일 경제 내에서 거래되는 자산들의 평균공분산은 양의 값을 갖게 된다.",
  "위험자산만으로 포트폴리오를 구성할 때보다 무위험자산까지 포함시켜 포트폴리오를 구성하면 투자자의 효용을 증가시킬 수 있다.",
  "위험회피적인 투자자는 불확실한 상황하에서 기대수익률의 극대화를 목표로 의사결정한다.",
  "두 개의 효율적 포트폴리오를 선형결합하면 새로운 효율적 포트폴리오를 생성할 수 있다."
 ],
 answer:[2]
},
{
 id:6,
 q:"B회사의 총자산은 10억원, 자기 자본은 2억원, 연간 매출액이 50억원이라고 하자. 매출은 모두 외상이며 1개월 후에 회수된다. 회수기간이 1개월일 때의 재무상태표는 아래와 같다. 외상매출금 회수기간이 2개월로 늦어지는 경우 이 회사의 부족한 자금규모는 얼마인가?<br><br><img src=\"problem6.jpg\" style=\"max-width:100%; border-radius:10px;\">",
 options:[
  "84,000(만원)",
  "88,000(만원)",
  "42,000(만원)",
  "44,000(만원)"
 ],
 answer:[2]
},
{
 id:8,
 q:"다음 서술 중 틀린 것을 모두 고르시오",
 options:[
  "유동성은 원재료 구입으로 인한 현금유출과 매출채권 회수로 인한 현금유입 사이의 시간간격에 큰 영향을 받는다.",
  "주주 입장에서 자기자본순이익률(ROE)은 높을수록 바람직하다.",
  "부채가 과도한 수준인 경우 주주는 과대투자나 과소투자의 유인이 생길 수 있고, 이는 기업가치를 감소시키게 된다.",
  "현금전환사이클이 단축되면 추가적인 운전자본을 조달해야 된다.",
  "정보비대칭하에서 자본조달비용을 고려하면 내부유보자금 -> 신주발행 -> 부채 순으로 자본을 조달하는 것이 유리하다."
 ],
 answer:[3,4]
},
{
 id:9,
 q:"다음 서술 중 틀린 것은?",
 options:[
  "고정자산은 매출액 변동에 따라 불규칙적으로 변한다.",
  "매출액 증가는 곧 필요자금의 감소로 해석하면 된다.",
  "현금의 수입과 지출을 추정하여 시기별 자금의 과부족을 예측할 수 있다.",
  "매출액이 크게 늘 것으로 예상된다면 자금사정에 큰 문제가 발생할 수 있다."
 ],
 answer:[1]
},
{
 id:10,
 q:"다음 설명 중 옳은 것을 모두 고르시오",
 options:[
  "기업경영에 있어 부채비율은 낮으면 낮을수록 좋다.",
  "매입채무회전기간이 늘어나면 운전자본을 추가로 조달해야 한다.",
  "매출액의 증가는 향후 필요한 운전자본을 증가시키게 된다.",
  "기업경영에 있어 이자보상비율은 높은 것이 바람직하다."
 ],
 answer:[2,3]
}
];

var selected={};
var submitted=false;

function getSelected(id){
  return selected[id] || [];
}

function render(){
  var quiz=document.getElementById('quiz');
  quiz.innerHTML='';

  for(var i=0;i<quizData.length;i++){
    (function(q, idx){
      var card=document.createElement('div');
      card.className='card';

      var title=document.createElement('div');
      title.innerHTML='<strong>'+(idx+1)+'. '+q.q+'</strong>';
      card.appendChild(title);

      if(submitted){
        var badge=document.createElement('span');
        badge.className='badge '+(isCorrect(q)?'ok':'no');
        badge.innerText=isCorrect(q)?'정답':'오답';
        card.appendChild(badge);
      }

      for(var j=0;j<q.options.length;j++){
        (function(opt, oi){
          var btn=document.createElement('button');
          btn.className='option';

          var sel=getSelected(q.id);
          if(sel.indexOf(oi)>-1) btn.className+=' selected';
          if(submitted && q.answer.indexOf(oi)>-1) btn.className+=' correct';
          if(submitted && sel.indexOf(oi)>-1 && q.answer.indexOf(oi)===-1) btn.className+=' wrong';

          btn.innerHTML=(oi+1)+'. '+opt;
          btn.onclick=function(){
            if(submitted) return;
            if(!selected[q.id]) selected[q.id]=[];
            var pos=selected[q.id].indexOf(oi);
            if(pos>-1){
              selected[q.id].splice(pos,1);
            }else{
              selected[q.id].push(oi);
            }
            render();
          };

          card.appendChild(btn);
        })(q.options[j], j);
      }

      if(submitted && !isCorrect(q)){
        var ans=document.createElement('div');
        ans.className='answer-text';
        var correctLabels=[];
        for(var k=0;k<q.answer.length;k++) correctLabels.push(q.options[q.answer[k]]);
        ans.innerText='정답: '+correctLabels.join(', ');
        card.appendChild(ans);
      }

      quiz.appendChild(card);
    })(quizData[i], i);
  }
}

function isCorrect(q){
  var a=getSelected(q.id).slice().sort().join();
  var b=q.answer.slice().sort().join();
  return a===b;
}

function submitQuiz(){
  submitted=true;
  var score=0;
  for(var i=0;i<quizData.length;i++){
    if(isCorrect(quizData[i])) score++;
  }

  var result=document.getElementById('result');
  result.style.display='block';
  result.innerText='결과: '+score+' / '+quizData.length;

  document.getElementById('wr1').innerText='내 답: '+(document.getElementById('w1').value||'없음');
  document.getElementById('wr2').innerText='내 답: '+(document.getElementById('w2').value||'없음');

  render();
  window.scrollTo(0,0);
}

function resetQuiz(){
  selected={};
  submitted=false;
  document.getElementById('result').style.display='none';
  document.getElementById('w1').value='';
  document.getElementById('w2').value='';
  document.getElementById('wr1').innerText='';
  document.getElementById('wr2').innerText='';
  render();
  window.scrollTo(0,0);
}

document.addEventListener('DOMContentLoaded', function(){ render(); });
</script>
</body>
</html>
