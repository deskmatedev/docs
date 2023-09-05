# 体验不同的语音引擎

桌妹使用了两种语音合成引擎方案。

## 基础语音能力：基于VITS的语音合成引擎

VITS是一个先进的语音合成模型，基于[Variational Inference Text-to-Speech（VITS）](https://arxiv.org/abs/2106.06103)。它结合了几种先前的TTS技术，包括Transformer、Gaussian Process和Flow-based模型，以产生高质量、自然发音的语音。

想象一下，你正在尝试让机器像人一样读出文本。这就是VITS要做的事情。VITS是一个高级的"朗读机器"，它将文字转化为像人类发声一样的语音。这样的机器如何工作呢？

首先，VITS像一个学生那样学习。它听很多真实的人声，同时阅读相应的文字。通过这种方式，它学习了文字和声音之间的关系。 当你给VITS一个句子时，它首先会像我们阅读文本时那样理解每一个词和其中的意思。接着，VITS会像一位演讲家那样，预测每个词应该持续多长时间，以及其强调和语调。有了上述信息后，VITS就会开始"朗读"这段文字。它会像人一样，制造出语音的特征。最后，VITS会对它生成的声音进行微调，使其听起来更像真实的人声。

团队的TTS工程师在现有VITS模型的基础上，优化了多个方面，包括中文多音字以及说话韵律的优化，并增加了基于情感因素的发音使得桌妹的语音回复更加自然富有情感。

基础语音能力是标准会员的权益之一。

?> _为什么选择VITS？_ 在众多的开源语音模型中，VITS是一个非常突出的，端到端的语音模型。相比其他模型，比如Tacotron 1/2、DeepSpeech、FastSpeech等，VITS在语音合成方面，可以生成更逼真、更自然的语音，并且在语音质量、语音流畅性和语音多样性等方面都更加出色。在性能优越的基础上，VITS模型的训练速度非常快，并且适用性非常广泛。综合以上几点，我们选择VITS作为我们的基础语音模型。

## 高级语音能力：基于微软定制神经网络声音（CNV）的语音合成引擎

微软定制神经网络声音（Custom Neural Voice - CNV）是微软公司研发的能够合成逼真、自然发音的语音。借助CNV优秀的发音效果，可以使妹妹们的声音更加动听，音质也会更好。团队基于CNV训练的语音模型在基础模型的基础上进一步提升了音色和音质，对情感的支持也更加出色。不仅如此，高级版语音也支持多种语言的发音，你甚至可以让桌妹教你学英语哦。

考虑到部署和使用的成本，基于CNV的高级语音能力是高级会员的权益之一。

?> _为什么选择CNV？_ 我们在考量商用语音模型时测试了市面上绝大多数产品的语音合成效果，微软的定制语音的综合表现是非常突出的。这也是为什么目前绝大多数自媒体创作者会使用微软的神经网络语音合成作为短视频的配音选择。

## VITS方案与CNV方案的对比

在体验上，VITS方案和CNV方案的效果接近，但CNV的使用体验更好、音质更高。

在优化上，桌妹团队会持续优化VITS方案中的语音模型，并不断针对新的优化方案训练新的模型。而对于CNV方案，我们也会继续跟进，确保方案的声音效果是官方最新的版本。

在使用上，VITS方案与CNV方案均需要通过网络传输数据，两个方案均被深度优化，降低了延迟，提升了使用的稳定性。

## 如何切换语音引擎

?> _TODO_