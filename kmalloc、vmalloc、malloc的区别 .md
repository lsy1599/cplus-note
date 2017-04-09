>kmalloc和vmalloc是分配的是内核的内存,malloc分配的是用户的内存
    kmalloc保证分配的内存在物理上是连续的,vmalloc保证的是在虚拟地址空间上的连续,malloc不保证任何东西(这点是自己猜测的,不一定正确)
    kmalloc能分配的大小有限,vmalloc和malloc能分配的大小相对较大
    内存只有在要被DMA访问的时候才需要物理上连续
    vmalloc比kmalloc要慢
