##############################################################################
# FILE:        moos-ivp-extend/src/CMakeLists.txt
# DATE:        2010/09/07
# DESCRIPTION: CMakeLists.txt file for the moos-ivp-extend source directory
##############################################################################


#============================================================================
# Add the libraries in the current directory to the include path
#============================================================================
FILE(GLOB LOCAL_LIBRARY_DIRS ./lib_*)
INCLUDE_DIRECTORIES(${LOCAL_LIBRARY_DIRS})

#============================================================================
# List the subdirectories to build...
#============================================================================
ADD_SUBDIRECTORY(iIMU_RazorAHRS)
ADD_SUBDIRECTORY(iSonar)
ADD_SUBDIRECTORY(iCISCREA)
ADD_SUBDIRECTORY(iCamera)
ADD_SUBDIRECTORY(iEchoSounder)
ADD_SUBDIRECTORY(pSensorViewer)
ADD_SUBDIRECTORY(pBuoyDetection)
ADD_SUBDIRECTORY(uJoystick)
ADD_SUBDIRECTORY(pSauceCSV)
#ADD_SUBDIRECTORY(pPipeDetection)
#ADD_SUBDIRECTORY(pLocalisationMask)
ADD_SUBDIRECTORY(pWallFollowing)
ADD_SUBDIRECTORY(iGPS)
ADD_SUBDIRECTORY(lib_common)
ADD_SUBDIRECTORY(lib_behaviors)
ADD_SUBDIRECTORY(pCameraLogger)
ADD_SUBDIRECTORY(pLocalizationSonar)
ADD_SUBDIRECTORY(pControl)
ADD_SUBDIRECTORY(uDeReCISCREA)
ADD_SUBDIRECTORY(pSimplePID)
ADD_SUBDIRECTORY(pDrawDetections)



##############################################################################
#                           END of CMakeLists.txt
##############################################################################

