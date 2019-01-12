---
title: "Second post"
date: 2019-01-10T22:09:13+09:00
draft: false
---
hugo new posts/hogehoge.mdコマンドで記事の作成ができます。
作業ディレクトリ直下でコマンドを打つ必要があるので、今の位置をlsコマンドで確認してからにしましょう。
**firstpost.md**は記事のタイトルなので$x^2 + \sin(x) = y^2$適宜名前を変えてください。
$$
x^2 + \sin(x) = y^2
$$

コードハイライトのテスト

{{< highlight python >}}
# 学習開始
    for i in range(1000):
        batch_xs, batch_ys = mnist.train.next_batch(100)
        sess.run(train_step, feed_dict={x: batch_xs, y_: batch_ys})
#        print sess.run(accuracy, feed_dict={x: batch_xs, y_: batch_ys})
    
    print sess.run(accuracy, feed_dict={x: mnist.test.images, y_: mnist.test.labels})
{{< / highlight >}}

{{< figure src="/images/test.png" title="Screenshot" class="center" width="640" height="320" >}}
$$
  \sum_{k=0}^{\infty} \frac{(2k)!}{2^{2k}(k!)^2} \frac{1}{2k+1} =
\prod\_{k=0}^{\infty} \frac{4k^2}{4k^2 - 1}
$$



