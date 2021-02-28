<h1 id="ocr-식품-원재료-분석기">OCR 식품 원재료 분석기</h1>
<p>식품의 원재료부분을 카메라로 촬영하면 어플 사용자들이 입력한 질병 혹은 알레르기 등을 토대로 건강에 해가 되지 않는 식품인지 판단하여 정보를 제공해주는 안드로이드 어플로 제작된 프로젝트입니다.<br>
이 프로젝트는 공부 목적의 비상업적 프로젝트입니다.</p>
<p>It is a project made with Android apps that provide information on whether the food is unhealthy based on diseases or allergies entered by application users.<br>
This project is a non-commercial project for study purposes.</p>
<h2 id="contributors">Contributors</h2>
<p><a href="https://github.com/SuHoTan">SuHoTan</a> : 데이터베이스 구축 및 연동, 이미지편집 및 OCR 기능개발</p>
<p><a href="https://github.com/LuneRemer">LuneRemer</a> : OCR 연구, OCR 후처리 알고리즘 개발</p>
<p><a href="https://github.com/DevYJKwon">DevYJKwon</a> : OCR 성능 비교, 카메라 기능개발 및 OCR 기능통합</p>
<p><a href="https://github.com/Sujinkim-625">Sujinkim-625</a> : 데이터 수집, 화면 레이아웃 개발</p>
<h2 id="개발환경">1. 개발환경</h2>
<blockquote>
<p>개발언어</p>
</blockquote>
<ul>
<li>JAVA 1.8</li>
</ul>
<blockquote>
<p>IDE</p>
</blockquote>
<ul>
<li>Android Studio</li>
</ul>
<blockquote>
<p>Database</p>
</blockquote>
<ul>
<li>SQLite</li>
</ul>
<blockquote>
<p>사용 라이브러리</p>
</blockquote>
<ul>
<li>Google Cloud vision</li>
<li>java-string-similarity-2.0.0(LCS(Longest Common Subsequence))</li>
<li>com.yalantis.ucrop</li>
<li>com.theartofdev.edmodo.cropper</li>
</ul>
<h2 id="시스템-구성도--프로세스">2. 시스템 구성도 &amp; 프로세스</h2>
<p><img src="md/%EC%8B%9C%EC%8A%A4%ED%85%9C%EA%B5%AC%EC%84%B1%EB%8F%84.PNG" alt="Alt"></p>
<hr>
<p><img src="md/%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4.PNG" alt="Alt"></p>
<h2 id="패키지-구조--데이터베이스">3. 패키지 구조 &amp; 데이터베이스</h2>
<p><img src="md/%ED%8C%A8%ED%82%A4%EC%A7%80%EA%B5%AC%EC%A1%B0.PNG" alt="Alt"></p>
<p><img src="md/%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4%EB%AA%A8%EB%8D%B8%EB%A7%81.PNG" alt="Alt"></p>
<h2 id="ocr-식품-원재료-분석기-주요-화면">4. OCR 식품 원재료 분석기 주요 화면</h2>
<h3 id="사용자-알레르기질병-정보-입력">4-1. 사용자 알레르기/질병 정보 입력</h3>
<p><img src="md/%EC%A7%88%EB%B3%91%EC%A0%95%EB%B3%B4%EC%9E%85%EB%A0%A5.PNG" alt="Alt"></p>
<hr>
<h3 id="카메라를-통한-원재료명-스캔">4-2. 카메라를 통한 원재료명 스캔</h3>
<ul>
<li>4-2-1. 카메라를 통한 원재료 스캔<br>
<img src="md/%EC%9B%90%EC%9E%AC%EB%A3%8C%EB%B6%84%EC%84%9D.gif" alt="Alt"></li>
</ul>
<hr>
<ul>
<li>4-2-2. 갤러리를 통한 원재료 스캔<br>
<img src="md/%EA%B0%A4%EB%9F%AC%EB%A6%AC%EC%9B%90%EC%9E%AC%EB%A3%8C%EB%B6%84%EC%84%9D.gif" alt="Alt"></li>
</ul>
<h2 id="setting-for-execution">5. Setting for execution</h2>
<ul>
<li>Project structure -&gt; Dependencies -&gt; jar Dependencies -&gt; directory of java-string-similarity-2.0.0.jar import</li>
<li>Gradle Synchronize<br>
<img src="md/%EC%84%B8%ED%8C%85.PNG" alt="Alt"></li>
</ul>
<h2 id="image-cropper-license">6. Image Cropper License</h2>
<p>Copyright 2017, Yalantis<br>
Licensed under the Apache License, Version 2.0 (the “License”);<br>
you may not use this file except in compliance with the License.<br>
You may obtain a copy of the License at<br>
<a href="http://www.apache.org/licenses/LICENSE-2.0">http://www.apache.org/licenses/LICENSE-2.0</a><br>
Unless required by applicable law or agreed to in writing, software<br>
distributed under the License is distributed on an “AS IS” BASIS,<br>
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.<br>
See the License for the specific language governing permissions and<br>
limitations under the License.</p>
<ul>
<li>com.theartofdev.edmodo.cropper<br>
Originally forked from edmodo/cropper.<br>
Copyright 2016, Arthur Teplitzki, 2013, Edmodo, Inc.<br>
Licensed under the Apache License, Version 2.0 (the “License”); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:<br>
<a href="http://www.apache.org/licenses/LICENSE-2.0">http://www.apache.org/licenses/LICENSE-2.0</a><br>
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an “AS IS” BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.</li>
</ul>

