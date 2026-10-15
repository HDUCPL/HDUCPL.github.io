---
title: "实验室简介"
date: 2026-01-01
layout: single
permalink: /labIntro/
author_profile: true
---

实验室目前包括两位副教授，一名博士后以及三个年级二十余位硕士生。主要进行光电成像、智能图像处理、计算光学成像以及机器视觉算法方向的研究。

<style>
	.lab-photo {
		width: 250px;
		height: 300px;
		object-fit: cover;
	}

	/* 成员之间的淡分隔线：两端渐隐，不抢视觉 */
	.member-divider {
		border: 0;
		height: 1px;
		width: 60%;
		margin: 3em auto 2.5em;
		background: linear-gradient(to right,
			rgba(128, 128, 128, 0) 0%,
			rgba(128, 128, 128, 0.3) 50%,
			rgba(128, 128, 128, 0) 100%);
	}

	/* 博士后图片占位：彩色流动动画 */
	.pending-photo {
		width: 250px;
		height: 300px;
		margin: 1.5em auto;
		display: flex;
		align-items: center;
		justify-content: center;
		color: #ffffff;
		font-size: 0.95em;
		letter-spacing: 0.2em;
		text-indent: 0.2em;
		text-shadow: 0 1px 4px rgba(0, 0, 0, 0.35);
		background: linear-gradient(120deg,
			#ff9a9e, #fbc2eb, #a18cd1, #84fab0, #f6d365, #ff9a9e);
		background-size: 400% 400%;
		animation: pending-flow 9s ease-in-out infinite;
	}

	@keyframes pending-flow {
		0%   { background-position: 0% 50%; }
		50%  { background-position: 100% 50%; }
		100% { background-position: 0% 50%; }
	}

	@media (prefers-reduced-motion: reduce) {
		.pending-photo { animation: none; }
	}

	/* ===== 研究生折叠卡片 ===== */
	.member-card {
		border-bottom: 1px solid rgba(128, 128, 128, 0.18);
		padding: 0.2em 0;
	}
	.member-card:last-of-type { border-bottom: 0; }

	.member-card > summary {
		list-style: none;              /* 去掉默认三角 */
		cursor: pointer;
		display: flex;
		align-items: baseline;
		flex-wrap: wrap;
		gap: 0.75em;
		padding: 0.85em 0;
		outline: none;
	}
	.member-card > summary::-webkit-details-marker { display: none; }
	.member-card > summary:hover .member-name { color: #6b8afd; }

	/* + / − 指示符 */
	.member-card > summary::before {
		content: "+";
		flex: 0 0 auto;
		width: 1.1em;
		font-size: 1.1em;
		line-height: 1;
		color: #9aa0a6;
		transition: transform 0.2s ease;
	}
	.member-card[open] > summary::before { content: "−"; color: #6b8afd; }

	.member-name {
		font-weight: 600;
		font-size: 1.05em;
		transition: color 0.2s ease;
	}
	.member-meta {
		font-size: 0.85em;
		color: #777;
	}

	.member-body {
		padding: 0.2em 0 1.4em 1.85em;  /* 与名字对齐，避开 + 号 */
	}
	.member-body::after { content: ""; display: table; clear: both; }
	.member-body p { margin: 0.8em 0 0; }

	@media (prefers-reduced-motion: reduce) {
		.member-card > summary::before,
		.member-name { transition: none; }
	}
</style>

## 实验室PI

<img src="/Lib_picture/zjf.jpg" alt="描述" class="align-center lab-photo">

赵巨峰

赵巨峰，博士，副教授，硕导，长期从事光电智能成像、AI+光学/能源/医疗等研究。近5年，主持各类项目18项，发表SCI论文50余篇，授权发明专利近30项并成功转让落地15项。目前担任浙江省光学学会理事，中国光学工程学会计算成像专业委员会青年委员，获浙江省科技进步奖、宁波市科学技术进步奖、昆山市双创人才计划支持等

<hr class="member-divider">

<img src="/Lib_picture/cgm.jpg" alt="描述" class="align-center lab-photo">

崔光茫

崔光茫，博士，副教授，硕导，主要从事计算光学成像、智能图像处理、机器视觉检测、深度学习算法研究。主持国家自然科学基金项目、浙江省公益研究计划/探索项目、企事业单位横向委托项目等，发表SCI论文50余篇，授权发明专利20余项。担任中国光学工程学会计算成像专业委员会青年委员，获宁波市科学技术进步奖，昆山市双创人才计划支持。

## 博士后

<div class="pending-photo">图片审批中</div>

华玮平
这人很神秘

## 研究生

以下个人简介为609全体成员集思广益所得（点击姓名展开）

<details class="member-card">
	<summary><span class="member-name">张天培</span><span class="member-meta">红外与可见光图像融合</span></summary>
	<div class="member-body">
		<!-- 张天培.png -->
		<img src="/Lib_picture/张天培植物版.gif" alt="张天培" class="align-center lab-photo">
		<p>SBTI: JOKE-R，实验室史上最强——六篇论文拥有者，健身界斜方肌之王，纯爱第一人，想唱就唱麦霸</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">刘昊宇</span><span class="member-meta">深度学习图像去模糊</span></summary>
	<div class="member-body">
		<!-- 刘昊宇.jpg -->
		<img src="/Lib_picture/刘昊宇植物版.gif" alt="刘昊宇" class="align-center lab-photo">
		<p>SBTI: ZZZZ，二次元20年深度用户，12,3456，咕咕嘎嘎</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">危晓婕</span><span class="member-meta">傅里叶叠层显微成像</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/危晓婕.jpg" alt="危晓婕" class="align-center lab-photo">
		<p>SBTI: LOVE-R，比比拉布，《知否》十级爱好者</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">廖福</span><span class="member-meta">散射成像</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/廖福.jpg" alt="廖福" class="align-center lab-photo">
		<p>实验室最神秘的人之一</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">郑钰辰</span><span class="member-meta">小目标检测</span></summary>
	<div class="member-body">
		<!-- 郑钰辰.jpg -->
		<img src="/Lib_picture/郑钰辰植物版.gif" alt="郑钰辰" class="align-center lab-photo">
		<p>SBTI: IMSB/SEXY/ATM-er，义乌小商品批发市场幕后老总<br>（次要研究方向：母猪产后护理）</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">崔伟泽</span><span class="member-meta">散射成像</span></summary>
	<div class="member-body">
		<!-- 崔伟泽.jpg -->
		<img src="/Lib_picture/崔伟泽植物版.gif" alt="崔伟泽" class="align-center lab-photo">
		<p>SBTI: LOVE-R，又能怎，138学号真实拥有者，一千天原崩双批，实验室食物链最底端人士，609信誉分大残选手，609林丹，魔丸，沉默男神</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">郝月生</span><span class="member-meta">三维重建</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/向日葵.gif" alt="郝月生" class="align-center lab-photo">
		<p>SBTI: SOLO，实验室著名植物大战僵尸高玩，放置一次可以对3*3范围内僵尸造成1800点伤害，头像可以和豌豆射手融合，609李宗伟</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">熊学锡</span><span class="member-meta">高光谱图像目标检测</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/熊学锡.jpg" alt="熊学锡" class="align-center lab-photo">
		<p>SBTI: BOSS，那么好，一个丧心病狂的高光谱目标检测识别与跟踪计算机视觉研究者，这张图片中的目标有0.01%的可能不是熊学锡。手机摔摔回收者，内审90分拥有者，脚本小程序手搓王者</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">李达</span><span class="member-meta">视觉检测</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/李达.png" alt="李达" class="align-center lab-photo">
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">柳展宏</span><span class="member-meta">散射成像？</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/刘展宏3.jpg" alt="柳展宏" class="align-center lab-photo">
		<p>SBTI: MALO，三人雀魂狗运王，展宏优选创始人，有氧做到无氧窒息者，沉默晒干者，609张继科</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">邵坚钢</span><span class="member-meta">光谱成像</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/邵坚钢.jpg" alt="邵坚钢" class="align-center lab-photo">
		<p>SBTI: SOLO，我的刀盾，杭电奥沙利文，杭电薛之谦，专利钉子户</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">石涣</span><span class="member-meta">傅里叶叠层显微成像</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/石涣.jpg" alt="石涣" class="align-center lab-photo">
		<p>第五人格头号玩家，牵制监管者半小时顶级高玩</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">井雨馨</span><span class="member-meta">红外小目标检测（两篇TOP持有者）</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/井雨馨.png" alt="井雨馨" class="align-center lab-photo">
		<p>SBTI: LOVE-R，实验室最强！！！Nature有力冲击者</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">黄瑜成</span><span class="member-meta">图像去模糊 & all-in-one 图像恢复</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/黄瑜成.jpg" alt="黄瑜成" class="align-center lab-photo">
		<p>SBTI: DEAD，实验室最强之二！！！诺奖有力冲击者</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">刘琰</span><span class="member-meta">研究方向待定</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/刘琰.jpg" alt="刘琰" class="align-center lab-photo">
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">欧阳俊杰</span><span class="member-meta">研究方向待定</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/欧阳俊杰.jpg" alt="欧阳俊杰" class="align-center lab-photo">
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">周宇豪</span><span class="member-meta">跨模态转译</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/周宇豪.jpg" alt="周宇豪" class="align-center lab-photo">
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">周遥</span><span class="member-meta">图像匹配</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/周遥.jpg" alt="周遥" class="align-center lab-photo">
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">张英杰</span><span class="member-meta">不均匀雾图复原与增强</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/张英杰.jpg" alt="张英杰" class="align-center lab-photo">
		<p>曾经的 idol</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">江鸿翔</span><span class="member-meta">点云与图像配准</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/江鸿翔.jpg" alt="江鸿翔" class="align-center lab-photo">
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">汪俊含</span><span class="member-meta">一体化天气退化修复</span></summary>
	<div class="member-body">
		<!-- 汪俊含.jpg -->
		<img src="/Lib_picture/汪俊含耄耋版.gif" alt="汪俊含" class="align-center lab-photo">
		<p>苦难陈述者，火锅狂炫者，下班光速者</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">王海莲</span><span class="member-meta">目标跟踪</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/王海莲.jpg" alt="王海莲" class="align-center lab-photo">
		<p>王姐好</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">莫建华</span><span class="member-meta">散射成像</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/莫建华.jpg" alt="莫建华" class="align-center lab-photo">
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">程龙</span><span class="member-meta">傅里叶叠层显微成像</span></summary>
	<div class="member-body">
		<!-- 程龙.jpg -->
		<img src="/Lib_picture/程龙遐蝶版.gif" alt="程龙" class="align-center lab-photo">
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">王嘉琪</span><span class="member-meta">图像去雾</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/王嘉琪.jpg" alt="王嘉琪" class="align-center lab-photo">
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">赵烨成</span><span class="member-meta">3DGS</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/赵烨成.jpg" alt="赵烨成" class="align-center lab-photo">
		<p>杰宝 idol 的忠实粉丝</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">徐晨赫</span><span class="member-meta">散射场景重现 / 扩散模型</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/徐晨赫.jpg" alt="徐晨赫" class="align-center lab-photo">
		<p>这个人很懒，什么都没留下</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">王培宏</span><span class="member-meta">红外与可见光图像融合</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/王培宏.jpg" alt="王培宏" class="align-center lab-photo">
		<p>SBTI:JOKER-R</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">徐颖馨</span><span class="member-meta">3D高斯</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/徐颖馨.jpg" alt="徐颖馨" class="align-center lab-photo">
		<p>财运追求者，麻将狂热者，KTV有氧者</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">伍毅</span><span class="member-meta">MRI图像分割</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/伍毅.jpg" alt="伍毅" class="align-center lab-photo">
		<p>SBTI：DRUNK  609石宇奇 2825张信哲  头衔：绝航单三只打最强一队/海斗只玩丢子/海斗tp回城/ 鸣潮十连三金/湘菜坚定拥护者/史迪仔十年老粉/鹅鸭杀信誉分扫不出共享单车之人/长麻高手</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">虞梓健</span><span class="member-meta">多模态机器视觉 / 小样本学习 / VLM</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/虞梓健.jpg" alt="虞梓健" class="align-center lab-photo">
		<p>ENFJ , 双鱼座 为世界上所有的美好而战！</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">鲁坤林</span><span class="member-meta">跨模态特征匹配</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/鲁坤林.jpg" alt="鲁坤林" class="align-center lab-photo">
		<p>迪耄，迪耄～</p>
	</div>
</details>

<details class="member-card">
	<summary><span class="member-name">黄光宇</span><span class="member-meta">一体化图像清晰化重建/遥感、自动驾驶场景拓展、3D目标检测</span></summary>
	<div class="member-body">
		<img src="/Lib_picture/黄光宇.jpg" alt="黄光宇" class="align-center lab-photo">
		<p>人格已分屏，精神很稳定，阿巴阿巴阿巴~</p>
	</div>
</details>

## 毕业生去向

刘洋	25年	南京市科学技术局
王继晨	24年	海康威视
项钦蕾	24年	浙农商数科
叶晓杰	21年	华为
毛海峰	21年	温州市文成县市场监督管理局