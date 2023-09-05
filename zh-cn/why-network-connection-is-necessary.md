# 为什么需要联网使用？

!> 桌妹需要互联网连接才能运行哦！

## AI推理需要占用大量计算资源

桌妹在运行时需要大量计算资源来进行AI推理（也就是记忆与回复生成）。尤其是当涉及到复杂的模型和大数据时，往往包含大量的参数和计算单元，它们需要的计算资源也会呈指数级增长。这样，本地设备可能无法提供足够的内存与计算能力。联网能使这些软件利用我们提供的更为强大的服务器资源，从而实现更快速、准确的推理。

## 本地推理还是服务端推理

- **本地推理**：优点是数据不需要在网络中传输，可以保证隐私和速度。但限于本地设备的内存与计算能力，可能导致推理时间增加。
- **服务端推理**：在强大的服务器上进行，可以利用更多的计算资源。结果会更快，并且能够处理更复杂的任务。但可能需要考虑数据传输的延迟和隐私问题。桌妹的数据传输经过了Dev们的优化，达到了很快的传输速度，并且数据在传输过程中使用了端到端的加密技术，确保安全可靠。

## 数据传输

联网使用可以确保桌妹和其背后的模型始终是最新的。随着新数据的不断加入，AI模型需要进行定期的训练和更新。联网可以保证用户始终使用的是最新、最优化的模型，从而获得更好的用户体验。

## 云端同步与跨设备协作

联网不仅仅是为了计算。对于桌妹，数据的云端同步也非常重要。未来我们计划更新其他设备端的应用（比如iOS或者安卓客户端）甚至是硬件产品。用户可以在不同的设备上获得一致的体验，并能轻松地在设备之间切换。此外，跨设备的协作也使得数据和设置的备份与恢复变得更加简单。