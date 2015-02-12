# Random-Walk-Simulator
A two dimensional random walk model simulator
The following readme is copied from the of the first version of main class.
/**
 * This program will simulate the behavior of random walk.
 * The user first specify the size of the stage, if the point goes out of the stage,
 * it will appear on the opposite side of the stage. For example, if a point goes 
 * beyond the top boundary of the stage, it will re-emerge at the botom. User may seperate
 * two numbers by space of a new line character("enter"). Press enter to confirm.
 * 
 * Then user will then be asked to select a mode.
 * Auto mode is for animated real-time random movement. Numbered mode is for a fixed
 * number of moves, without real-time animation.
 * 
 * The auto mode will update every 20 milisecond, each update will contain 500 
 * random movements. The point will change color every 200 updates to make the movement
 * pattern more clear.
 * 
 * If the numbered mode is chosen, user will be prompted to enter the number of moves desired.
 * The number should not exceed the maximam number of a long integer.
 * The numbers will be evenly divided to 12 parts, each in a different color.
 * For correct representation of colors, the entered number should be a multiple
 * of 500 and should be greater than 60000
 * 
 * After the window is closed for auto mode, or after the generation is finished
 * for numbered mode, a png file,whih contains the snapshot of the random movement, 
 * will be created on the directory where source file is stored. The name of the 
 * png file will be <number_of_movements-curent_time-current_date>
 * 
 * The user should be responsible for correctness of input, for input-validation
 * is not implemented.
 * 
 * @author Guanqing Yan
 * @wordpress: thethirduniverse.wordpress.com
 * */
