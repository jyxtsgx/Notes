## Redux 是一个状态可预测的JS容器。
#### 如何在应用程序的整个生命周期内维持所有数据？
> 以你想要的方式维持这些数据，例如：JavaScript对象、数组、不可变数据，等等。
我们把应用程序的数据称为状态，因为我们所说的数据会随着时间的推移而变化，这其实就是应用的状态。
我们把这些状态信息转交给Redux。

### 如何修改这些数据？
> 我们使用reducer函数修改数据
reducer函数action的订阅者
reducer函数只是一个纯函数，它接收应用程序的当前状态以及发生的action，然后返回修改后的新状态。

### 如何把数据变更传播到整个应用程序？
> 使用订阅者来监听状态的变更情况。

    总之 Redux 提供了
    1.存放应用程序状态的容器
    2.一种把action分发到状态修改器的机制，这里的状态修改器就是reducer函数。
    3.监听状态变化的机制。