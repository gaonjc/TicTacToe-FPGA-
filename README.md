## TicTacToe-FPGA-
## TicTacToe implemented on the Nexys A7100T using Xilinx Vivado with UART interface
controls: 4 buttons for up down left right, middle button for select will be an X or an O based on player status on two rightmost seven segment displays).
Serial terminal will display grid with numbers representing the states on the FSM also shown on the 4th seven segment display from the left.
Once a player selects a square it cannot be overwritten until the CPU reset button is pressed.
The player can only select squares that still have a number in them.
Red RGB LED for player 1 Blue for player 2, Green for Win state, Yellow for tie state.
# The top module can be found [*here*](https://github.com/gaonjc/TicTacToe-FPGA-/blob/main/src/tictactoe_main.v)
# The FSM module responsible for sending ASCII to the terminal can be found [*here*](https://github.com/gaonjc/TicTacToe-FPGA-/blob/main/src/tictactoe_uart.v)
## Physical FPGA Demo ![demo](https://github.com/gaonjc/TicTacToe-FPGA-/blob/main/TicTacToeDemo.gif)

## Serial Terminal Demo ![demo](https://github.com/gaonjc/TicTacToe-FPGA-/blob/main/TeraTermSerial.gif)
