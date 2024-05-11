# This template runs Blinky on STs NUCLEO-64 STM32L010 board.

Clone this template:

```git clone xxx```

cd into ```embassy-template-stm32l0``` and type

```cargo run --bin embassy-template-stm32l0```

This should result in

```
Compiling embassy-template-stm32l0 v0.1.0 (/home/rob/Github/emb-usb)
  Finished dev [unoptimized + debuginfo] target(s) in 0.29s
    Running `probe-rs run --chip STM32L010RBTx target/thumbv6m-none-eabi/debug/embassy-template-stm32l0`
      Erasing ✔ [00:00:08] [##################################] 59.00 KiB/59.00 KiB @ 6.63 KiB/s (eta 0s )
      Programming ✔ [00:00:05] [#################################] 59.00 KiB/59.00 KiB @ 10.67 KiB/s (eta 0s )    Finished in 14.44s
```





  
runner = "probe-rs run --chip STM32L010RBTx"
