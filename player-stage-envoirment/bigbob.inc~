define bigbob position
(
     
      # the shape of Bigbob

    block( 
    points 8
    point[0] [-0.2 0.12]
    point[1] [-0.2 -0.12]
    point[2] [-0.12 -0.2555]
    point[3] [0.12 -0.2555]
    point[4] [0.2 -0.12]
    point[5] [0.2 0.12]
    point[6] [0.12 0.2555]
    point[7] [-0.12 0.2555]
    z [0 0.22]
  )

   
 
 color "black"			# Default color.
  drive "diff"		 	# Differential steering model.
  gui_nose 0                  	# Draw a nose on the robot so we can see which way it points
  obstacle_return 2           	# Can hit things.
  ranger_return 0.5            	# reflects sonar beams
  blob_return 1               	# Seen by blobfinders  
  fiducial_return 1           	# Seen as "1" fiducial finders

  localization "gps"         	  
  localization_origin [0 0 0 0] 	# Start odometry at (0, 0, 0).

# actual size
  size [0.3 0.2 0.2]   # sizes from MobileRobots' web site

     bigbobs_sonars()
)


define bigbobs_sonar sensor
(
    # define the size of each transducer [xsize ysize zsize] in meters
    size [0.01 0.05 0.01 ] 
    # define the range bounds [min max]
    range [0 2]
    # define the angular field of view in degrees
    fov 10
   # define the number of samples spread over the fov
  samples 1
	# define the color that ranges are drawn in the gui
	color_rgba [ 0 1 0 0.8 ] 
)

define bigbobs_sonars ranger
( 


 	bigbobs_sonar( pose [ 0 0 0 0]) 
	bigbobs_sonar( pose [ 0 0 0 5])
	bigbobs_sonar( pose [ 0 0 0 -5])
	bigbobs_sonar( pose [ 0 0 0 10])
	bigbobs_sonar( pose [ 0 0 0 -10])


	bigbobs_sonar( pose [ 0 0 0 80]) 
	bigbobs_sonar( pose [ 0 0 0 85])
	bigbobs_sonar( pose [ 0 0 0 90])
	bigbobs_sonar( pose [ 0 0 0 95])
	bigbobs_sonar( pose [ 0 0 0 100])
	


	bigbobs_sonar( pose [ 0 0 0 170])
	bigbobs_sonar( pose [ 0 0 0 175])
	bigbobs_sonar( pose [ 0 0 0 180])
	bigbobs_sonar( pose [ 0 0 0 -175])
	bigbobs_sonar( pose [ 0 0 0 -170])

	

 	bigbobs_sonar( pose [ 0 0 0 -80]) 
	bigbobs_sonar( pose [ 0 0 0 -85])
	bigbobs_sonar( pose [ 0 0 0 -90])
	bigbobs_sonar( pose [ 0 0 0 -95])
	bigbobs_sonar( pose [ 0 0 0 -100])
	
)



define goal position
(
     
      # the shape of Bigbob

    block( 
    points 4
    point[0] [0 0]
    point[1] [0 1]
    point[2] [1 1]
    point[3] [1 0]
   
    z [0 0.22]
  )

   
 
  color "red"			# Default color.
  drive "diff"		 	# Differential steering model.
  gui_nose 0                  	# Draw a nose on the robot so we can see which way it points
  obstacle_return 0           	# Can hit things.
  ranger_return 0.5            	# reflects sonar beams
  blob_return 0               	# Seen by blobfinders  
  fiducial_return 0           	# Seen as "1" fiducial finders

  localization "gps"         	  
  localization_origin [0 0 0 0] 	# Start odometry at (0, 0, 0).

# actual size
  size [0.9 0.9 0]   # sizes from MobileRobots' web site

)


define blo position
(
     
      # the shape of Bigbob

    block( 
    points 4
    point[0] [0 0]
    point[1] [1 0]
    point[2] [1 1]
    point[3] [0 1]
   
    z [0 0.22]
  )

   
 
  color "black"			# Default color.
  drive "diff"		 	# Differential steering model.
  gui_nose 1                  	# Draw a nose on the robot so we can see which way it points
  obstacle_return 1           	# Can hit things.
  ranger_return 0.5            	# reflects sonar beams
  blob_return 1               	# Seen by blobfinders  
  fiducial_return 1           	# Seen as "1" fiducial finders

  localization "gps"         	  
  localization_origin [0 0 0 0] 	# Start odometry at (0, 0, 0).

# actual size
  size [0.9 0.9 0.8]   # sizes from MobileRobots' web site

)





