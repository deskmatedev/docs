# Experience Different Voice Engines


Desk Mate utilizes two voice synthesis engine solutions.


## Basic Voice: VITS-based Voice


VITS is an advanced voice synthesis model based on [Variational Inference Text-to-Speech (VITS)](https://arxiv.org/abs/2106.06103). It integrates several prior TTS technologies, including Transformer, Gaussian Process, and Flow-based models, to produce high-quality, naturally pronounced voices.

Imagine trying to make a machine read text like a human. That's what VITS does. VITS acts as an advanced "reading machine" that translates text into human-like vocalization. How does such a machine work?

First, VITS learns like a student. It listens to many real human voices while reading the corresponding text. In this way, it learns the relationship between text and sound. When you provide VITS with a sentence, it first understands each word and its meaning, just as we read text. Then, VITS, acting like a speaker, predicts how long each word should last and its emphasis and intonation. With this information, VITS starts "reading" the text. It creates voice features just like humans. Finally, VITS fine-tunes the voice it generated to make it sound more like a real human.

Our TTS engineering team, building on the existing VITS model, optimized several aspects, including Chinese polyphonic characters and speaking rhythm, and added emotion-based pronunciation, making Desk Mate's voice responses more natural and emotional.

Basic voice capability is one of the standard member benefits.


?> _Why VITS?_ Among the many open-source voice models, VITS stands out as a highly remarkable, end-to-end voice model. Compared to other models, such as Tacotron 1/2, DeepSpeech, FastSpeech, etc., VITS can generate more realistic, more natural voices, and is superior in voice quality, fluency, and diversity. With its excellent performance, VITS trains very fast and is very versatile. Considering all these, we chose VITS as our basic voice model.


## Advanced Voice: Microsoft Custom Neural Voice


Microsoft's Custom Neural Voice (CNV) is a voice synthesis developed by Microsoft that can produce realistic, natural pronunciations. With CNV's excellent pronunciation effects, the voices of the virtual girls can sound more pleasant and of higher quality. The team's CNV-trained voice model further enhanced the timbre and quality based on the basic model, and the support for emotions is also outstanding. Moreover, the advanced version of the voice also supports pronunciation in various languages; you can even let Desk Mate teach you English.

Considering deployment and usage costs, the CNV-based advanced voice capability is a benefit for premium members.


?> _Why CNV?_ We tested the voice synthesis performance of most commercial voice models on the market, and Microsoft's custom voice stood out in terms of comprehensive performance. This is also why most content creators currently use Microsoft's neural voice synthesis for short video voiceovers.


## Comparison Between VITS and CNV Solutions


In terms of experience, the VITS and CNV solutions are close in performance, but CNV offers a better user experience with higher audio quality.

In optimization, the Desk Mate team will continuously improve the voice model in the VITS solution and continuously train new models for new optimization schemes. For the CNV solution, we will also keep updating to ensure that the voice effect is the official latest version.

In usage, both the VITS and CNV solutions require data to be transmitted over the network. Both solutions have been deeply optimized, reducing latency and enhancing stability.


## How to Switch Voice Engines


?> _TODO_
