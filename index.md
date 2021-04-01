## 등기가 우선입니다
![공문](/document.png)
<br/>
<br/>

<a name="calc"></a>
## [최악의 경우를 알아보자! 추가분담금 계산기](#calc)
조합원 여러분들이 쉽게 **현재 조합이 입은 큰 손실에 대한 추가분담금을 미리 계산해볼 수 있는 계산기**를 만들었습니다.  
**매일 늘어나는 이자가 적용**되며, 작은 손실이 여럿 더 있지만 아직 포함 하지 않았습니다.
**이번 등기총회가 가결 안되었을 때의 최악의 경우를 가정 하였습니다. 우리가 등기 빨리 내면서, 협상한다면 줄일 수 있는 비용이 많습니다!**  
<br />
<br />
_무권대리인(전미X)이 사용한 금액은 현재 제외 되어있으나,  
우리가 추인(추후인정) 하면 손해액에 추가할 예정입니다._
<br />
<br />
선생님의 권리가액은?
<br />
<input id="your_money" value="0" type="number" size="7">만원
<br>
현재 조합의 손해액은 총
<span id="total_loss"></span>
입니다.
<br>
현재 비례율은
<span id="current_percentage"></span>
입니다.
<font color="red"><b>
귀하의 현재 추가 분담금은 <span id="your_loss"></span>입니다.
</b></font>
1년 후, 조합의 손해액은 총
<span id="later_total_loss"></span>
입니다.
<br>
1년 후, 비례율은
<span id="later_current_percentage"></span>
입니다.
<font color="red"><b>
1년 후, 추가 분담금은 <span id="later_your_loss"></span>입니다.
</b></font>
#### 손해액 계산에 포함된 내역은 다음과 같습니다.
<div id="detail">
</div>

{% include new_analytics.html %}
{% include compute_loss.html %}
