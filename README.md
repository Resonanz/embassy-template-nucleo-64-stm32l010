# This template runs Embassy's (https://github.com/embassy-rs/embassy) Blinky code on STs NUCLEO-64 STM32L010 evaluation board.

Note: This eval board's microcontroller is an STM32L010RBT6.

Clone this template:

```git clone https://github.com/Resonanz/embassy-template-stm32l0.git```

cd into ```embassy-template-stm32l0``` and compile and run using:

```cargo run --bin embassy-template-stm32l0```

This should eventually result in:

```
Compiling embassy-template-stm32l0 v0.1.0 (/home/Github/embassy-template-stm32l0)
  Finished dev [unoptimized + debuginfo] target(s) in 0.29s
    Running `probe-rs run --chip STM32L010RBTx target/thumbv6m-none-eabi/debug/embassy-template-stm32l0`
      Erasing ✔ [00:00:08] [##################################] 59.00 KiB/59.00 KiB @ 6.63 KiB/s (eta 0s )
      Programming ✔ [00:00:05] [#################################] 59.00 KiB/59.00 KiB @ 10.67 KiB/s (eta 0s )    Finished in 14.44s
```

The Blinky program code has compiled and uploaded into the microcontroller on the eval board. The green LED on the eval board should be blinking on and off.

To change the LED flashing rate, edit ```main.rs``` then save and recompile.



  

