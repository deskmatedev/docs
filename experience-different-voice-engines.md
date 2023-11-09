# Experience Different Voice Engines


Deskmate uses two speech synthesis engine solutions.


## Standard Voice: VITS-based Voice


VITS is an advanced speech synthesis model based on [Variational Inference Text-to-Speech (VITS)](https://arxiv.org/abs/2106.06103). It combines several previous TTS technologies, including Adversarial Learning, Transformer, Gaussian Process, and Flow-based models, to produce high-quality, natural-sounding speech.

Imagine trying to get a machine to read text like a human. That's what VITS does. VITS is a sophisticated "reading machine" that converts text into speech that sounds like it was spoken by a human. How does such a machine work?

First, VITS learns like a student. It listens to a lot of real human voices, while reading the corresponding text. Through this way, it learns the relationship between text and sound. When you give VITS a sentence, it will first understand each word and its meaning, just as we do when we read text. Then, VITS will predict how long each word should last, as well as its emphasis and intonation, just like a speaker. With this information, VITS will begin to "read" the text. It will create the characteristics of speech, just like a human. Finally, VITS will fine-tune the sound it generates to make it sound more like real human speech.

The TTS engineers on the team have optimized several aspects, including the optimization of Chinese polysyllabic characters and speech rhythm, and the addition of pronunciation based on emotional factors, making Deskmate's voice responses more natural and emotional, based on the existing VITS model.

Basic speech ability is one of the benefits of standard members.


?> _Why VITS?_ Among the many open-source speech models, VITS is a very outstanding end-to-end speech model. Compared to other methods, such as Tacotron 1/2, DeepSpeech, and FastSpeech, VITS has improved the unnaturalness of other methods, such as the inefficient duration predictor, the complex input format that makes it impossible to generate high-quality speech, the inefficient duration predictor, the slow training speed, the strong dependence on phonemes, and the strong dependence on phoneme conversion.

In terms of speech synthesis, VITS can generate more realistic and natural speech, and is more outstanding in terms of speech quality, speech fluency, and speech diversity. On the basis of superior performance, the VITS model has a very fast training speed and is very versatile. Based on the above points, we chose VITS as our basic speech model.


## Advanced Voice: Azure Custom Neural Voice


Azure Custom Neural Voice (CNV) is a speech synthesis engine developed by Microsoft that can synthesize realistic and natural-sounding speech. With the excellent sound quality of CNV, the voices of the sisters can be more melodious and the sound quality will also be better. The speech model trained by the team based on CNV further enhances the tone and sound quality of the basic model, and also provides better support for emotions. In addition, the advanced voice also supports the pronunciation of multiple languages, so you can even let Deskmate teach you Chinese.

Considering the cost of deployment and use, the advanced speech ability based on CNV is a benefit for high-level members.


?> _Why CNV?_ When considering commercial speech models, we tested the speech synthesis effects of most products on the market. The overall performance of CNV is very outstanding. This is also why the vast majority of self-media creators currently use Azure's neural network speech synthesis as the choice for dubbing short videos.


## Comparison Between VITS and CNV Solutions


In terms of experience, the VITS and CNV schemes are similar, but the CNV scheme has a better user experience and higher sound quality.

In terms of optimization, the Deskmate team will continue to optimize the speech model in the VITS scheme and constantly train new models for new optimization schemes. For the CNV scheme, we will also continue to follow up, ensuring that the sound quality of the scheme is the latest official version.

In terms of use, both the VITS and CNV schemes require data transmission over the network. Both schemes have been deeply optimized to reduce latency and improve stability of use.


## How to Switch Voice Engines


In Settings > General > Sound > Speech generation model selection, users can manually select different speech synthesis engines (VITS or CNV) to experience different voices, and then adjust the selection of speech synthesis engines according to their personal preferences and needs.

Note: You need to purchase memberships in order to get voice response!
