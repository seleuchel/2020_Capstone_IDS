Capstone : DDOS 탐지 AutoEncoder IDS + Django 모니터링 서비스
=====================================================================
<img src="https://img.shields.io/badge/-Python-%233776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/-Django-%23092E20?style=flat-square&logo=Django&logoColor=white"/> <img src="https://img.shields.io/badge/-Keras-%23FF6F00?style=flat-square&logo=TensorFlow&logoColor=white"/> 
## Setting
> 이 레포지토리를 git clone 해줍니다.
<pre><code>git clone [이 git repository 주소]</pre></code>
> setting & module install
<pre><code>cd 2020_Capstone_IDS</code></pre>
<pre><code>chmod 777 settinginstall.sh</code></pre>
<pre><code>./settinginstall.sh</code></pre>
------------------------------------------------------------------
## IDS 실행
> 1. Django 실행 
#### 새로운 터미널 창을 띄우고 진행합니다.
<pre><code>cd mysite</pre></code>
<pre><code>sudo python3 manage.py runserver</pre></code>

> 2. IDS 실행
#### 새로운 터미널 창을 띄우고 진행합니다.
<pre><code>cd Capstone_DDOS_IDS</pre></code>
<pre><code>sudo python3 DDOS_IDS.py</pre></code>
------------------------------------------------------------------
## IDS 실행
> 임시계정
<pre><code>id : text / pw : 1234</pre></code>
------------------------------------------------------------------
## 연계 스마트미터기
https://github.com/seleuchel/Capstone_smartmeter
