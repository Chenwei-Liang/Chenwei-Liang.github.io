---
title: "An Efficient and Noise-Robust Audiovisual Encoder for Audiovisual Speech Recognition"
collection: publications
category: conferences
permalink: 
link: "https://www.isca-archive.org/interspeech_2023/li23k_interspeech.pdf"
excerpt: '[Zhengyang Li](https://www.tu-braunschweig.de/en/ifn/institute/dept/sv/li), **Chenwei Liang**, [Timo Lohrenz](https://scholar.google.com/citations?user=9u1wQE0AAAAJ&hl=de), [Marvin Sach](https://www.tu-braunschweig.de/en/ifn/institute/dept/sv/sach), [Björn Möller](https://www.tu-braunschweig.de/ifn/institut/team/sv/moeller), [Tim Fingscheidt](https://www.tu-braunschweig.de/ifn/institut/abt/sv/prof-dr-ing-tim-fingscheidt)'
date: 2023-08-20
venue: 'Interspeech'
paperurl: 'https://www.isca-archive.org/interspeech_2023/li23k_interspeech.pdf'
citation: 
teaser_gif: '/images/AV-Encoder.png'
---

Boosted by self-supervised learning (SSL) on large amounts of unlabeled data, computationally demanding transformer-based audiovisual ASR (AV-ASR) achieves state-of-the-art performance. In this work, we are the first to propose teacher-student model distillation for an efficient and noise-robust AV encoder for AV-ASR. First, we compare two options for the teacher, a non-task-specific and a task-specific one. Second, we investigate the design and the components in the student neural network. Third, we explore loss function choices during distillation. By distillation with a simplified loss function, the final efficient conformer-based student has 69% fewer parameters and 23% less computational power than the teacher, but excels the baseline student with a WER of 4.6% (11.4%) in clean condition, and with 20.2% (35.7%) in 0dB babble noise. On average over noise types in 0dB SNR, our proposed student even achieves more than 50% relative WER reduction compared to the baseline student.
