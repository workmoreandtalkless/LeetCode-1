### 1564.Put-Boxes-Into-the-Warehouse-I

这是一道经典题，比较简单的贪心策略是从高低遍历盒子。找到第一个能fit第一个仓库的盒子，装进去；然后找下一个能fit第二个仓库的盒子，装进去... 直至盒子遍历完或者仓库遍历到底。最终输出这个过程中fit了几次。