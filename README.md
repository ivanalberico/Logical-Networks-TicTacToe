# Logical-Networks-TicTacToe
Graded project of the course "Logical Networks", Tongji University Shanghai (Fall 2018).  Design of the game Tic Tac Toe using digital logic components in Proteus Design Suite environment.

<p align="center">
  <img src="https://user-images.githubusercontent.com/64502909/140420649-365f55e5-c047-4732-a9ff-b1105e727ae4.png">
</p>

#
The whole circuit is composed by 9 LEDs which represent the 9 boxes of the 3x3 grid. Push buttons are used to switch on the LEDs and each LED represents the moves of both two players, instead of using two LEDs to represent each box of the grid. For doing that we used bi-color LEDs. The final result will be shown by other two LEDs, one for win and one for draw. We also designed a stopwatch that displays the duration of each match.

#
Inputs given by switches are recognized as either 1st or 2nd player move and they are stored in flip-flops. The LEDs are connected to the outputs of the flip-flops. Winning or drawing condition is also checked from the outputs of the flip-flops. 

<br/><br/>  
# Some pictures of the implementation

<p align="center">
  <img src="https://user-images.githubusercontent.com/64502909/140421145-c73b0315-cbe9-4d8c-abc8-389099685c1a.PNG">
  <img src="https://user-images.githubusercontent.com/64502909/140421172-68786fff-0b7a-4db0-9b98-49752b0f6872.PNG">
  <img src="https://user-images.githubusercontent.com/64502909/140421775-f2262ed5-338d-46c4-ad20-89456fdc2c76.PNG">
  <img src="https://user-images.githubusercontent.com/64502909/140421810-ed77cf96-2625-4ada-adb1-0a9cb35a396a.PNG">
  <img src="https://user-images.githubusercontent.com/64502909/140421316-a3988694-5f22-477e-a773-c14155fd9ac7.PNG">
  <img src="https://user-images.githubusercontent.com/64502909/140421446-cfe1ac69-f1e0-45d4-ad17-b93c04bafd07.PNG">
</p>
