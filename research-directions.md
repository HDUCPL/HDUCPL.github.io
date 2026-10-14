---
title: "实验室研究方向"
date: 2026-10-14
layout: single
permalink: /research-directions/
author_profile: true
---


致力于研发新一代的智能成像和计算传感技术，研究计算光学成像理论方法，探索新型光电成像机理，开展先进光电成像探测仪器研制，结合深度学习策略，创新多光学波段、运动模糊复原、散射介质成像、叠层显微成像、高光谱等成像方式及数学理论算法，开拓其在生命与生物科学、智能化制造、遥感监测、军事国防、新能源智能运维等诸多前沿应用。

<style>
	/* ===== 研究方向折叠卡片 ===== */
	.topic-card {
		border-bottom: 1px solid rgba(128, 128, 128, 0.18);
	}
	.topic-card:last-of-type { border-bottom: 0; }

	/* summary 排成原来的 h2 观感 */
	.topic-card > summary {
		list-style: none;
		cursor: pointer;
		display: flex;
		align-items: baseline;
		flex-wrap: wrap;
		gap: 0.6em;
		margin: 0;
		padding: 0.85em 0;
		font-family: "San Francisco", "Source Sans Pro", "Helvetica Neue", Arial, sans-serif;
		font-weight: 700;
		font-size: 1.25em;
		line-height: 1.35;
		color: inherit;
		outline: none;
	}
	.topic-card > summary::-webkit-details-marker { display: none; }
	.topic-card > summary:hover { color: #6b8afd; }

	/* + / − 指示符 */
	.topic-card > summary::before {
		content: "+";
		flex: 0 0 auto;
		font-weight: 400;
		font-size: 0.9em;
		color: #9aa0a6;
	}
	.topic-card[open] > summary::before { content: "−"; color: #6b8afd; }

	/* 图片区：宽屏并排，窄屏自动堆叠 */
	.topic-body {
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
		align-items: flex-start;
		gap: 1.2em;
		padding: 0.3em 0 1.6em;
	}
	.topic-body img {
		flex: 1 1 260px;
		min-width: 0;
		max-width: 620px;
		height: auto;
		margin: 0 auto;
	}
	.topic-body::after { content: ""; display: table; clear: both; }
	.topic-note {
		flex: 1 1 100%;
		margin: 0;
		font-size: 0.9em;
		color: #888;
		text-align: center;
	}

	.toolbar { margin: 1.5em 0 0.2em; }
	.toolbar button {
		font-size: 0.85em;
		padding: 0.35em 1em;
		border: 1px solid rgba(128, 128, 128, 0.35);
		border-radius: 3px;
		background: transparent;
		cursor: pointer;
	}
	.toolbar button:hover { border-color: #6b8afd; color: #6b8afd; }

	@media (prefers-reduced-motion: reduce) {
		.topic-card > summary,
		.topic-card > summary::before { transition: none; }
	}
</style>

<p class="toolbar"><button type="button" id="toggleAll">展开全部</button></p>

<details class="topic-card">
	<summary>光谱成像与光谱目标检测</summary>
	<div class="topic-body">
		<img src="/research_picture/spectrum.png" alt="网络差没加载出来">
	</div>
</details>

<details class="topic-card">
	<summary>叠层成像/远距离叠层宏观成像</summary>
	<div class="topic-body">
		<img src="/research_picture/FPM.png" alt="网络差没加载出来">
	</div>
</details>

<details class="topic-card">
	<summary>MRI图像分割与目标检测(罕见病灶的分割)</summary>
	<div class="topic-body">
		<img src="/research_picture/med.png" alt="网络差没加载出来">
	</div>
</details>

<details class="topic-card">
	<summary>散射场景重建</summary>
	<div class="topic-body">
		<img src="/research_picture/散射.png" alt="网络差没加载出来">
		<img src="/research_picture/haze.png" alt="网络差没加载出来">
	</div>
</details>

<details class="topic-card">
	<summary>3D高斯重建/点云配准</summary>
	<div class="topic-body">
		<img src="/research_picture/point_cloud1.png" alt="网络差没加载出来">
		<img src="/research_picture/point_cloud2.png" alt="网络差没加载出来">
	</div>
</details>

<details class="topic-card">
	<summary>多模态机器视觉</summary>
	<div class="topic-body">
		<p class="topic-note">研究中</p>
	</div>
</details>

<details class="topic-card">
	<summary>（一体化）图像清晰复原</summary>
	<div class="topic-body">
		<img src="/research_picture/deblur.png" alt="网络差没加载出来">
		<img src="/research_picture/aioir.png" alt="网络差没加载出来">
	</div>
</details>

<details class="topic-card">
	<summary>红外可见光融合</summary>
	<div class="topic-body">
		<img src="/research_picture/visibal_light.png" alt="网络差没加载出来">
	</div>
</details>

<details class="topic-card">
	<summary>跨模态特征匹配</summary>
	<div class="topic-body">
		<p class="topic-note">研究中</p>
	</div>
</details>

<details class="topic-card">
	<summary>目标检测</summary>
	<div class="topic-body">
		<img src="/research_picture/small_target.png" alt="网络差没加载出来">
	</div>
</details>

<script>
	(function () {
		var btn = document.getElementById('toggleAll');
		var cards = document.querySelectorAll('.topic-card');
		if (!btn || !cards.length) return;
		var allOpen = true;                       // 首条默认展开，其余收起
		btn.addEventListener('click', function () {
			allOpen = !allOpen;
			for (var i = 0; i < cards.length; i++) cards[i].open = allOpen;
			btn.textContent = allOpen ? '收起全部' : '展开全部';
		});
	})();
</script>