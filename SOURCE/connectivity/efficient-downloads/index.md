> 编写:[kesenhoo](https://github.com/kesenhoo)

> 校对:

# 高效下载
在这一章，我们将学习为了最小化某些操作对电量的影响是如何处理下载，网络连接，尤其是无线电连接的。

下面几节课会演示了如何使用缓存caching，轮询polling，预取prefetching等技术来计划与执行下载操作。
我们还会学习无线电波的power-use属性配置是如何影响我们对于在何时，用什么，以何种方式来传输数据的选择。
当然这些选择是为了最小化对电池寿命的影响。

**Dependencies and prerequisites**

Android 2.0 (API Level 5) or higher

**You should also read**
[Optimizing Battery Life](http://developer.android.com/training/monitoring-device-state/index.html)

## Lessons
* **Optimizing Downloads for Efficient Network Access[使用有效的网络连接方式来最优化下载]**

This lesson introduces the wireless radio state machine, explains how your app’s connectivity model interacts with it, and how you can minimize your data connection and use prefetching and bundling to minimize the battery drain associated with your data transfers.

<!-- more -->

* **Minimizing the Effect of Regular Updates[优化常规更新操作的效果]**

  This lesson will examine how your refresh frequency can be varied to best mitigate the effect of background updates on the underlying wireless radio state machine.

* **Redundant Downloads are Redundant[重复的下载是冗余的]**

  The most fundamental way to reduce your downloads is to download only what you need. This lesson introduces some best practices to eliminate redundant downloads.

* **Modifying your Download Patterns Based on the Connectivity Type[根据网络连接类型来更改下载模式]**

  When it comes to impact on battery life, not all connection types are created equal. Not only does the Wi-Fi radio use significantly less battery than its wireless radio counterparts, but the radios used in different wireless radio technologies have different battery implications.
