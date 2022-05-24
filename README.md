# Geant4-IC

                 ------------------------Packets---------------------------


sudo apt install \
git dpkg-dev cmake g++ gcc binutils \
libx11-dev libxmu-dev libxpm-dev libxft-dev libxext-dev xlibmesa-glu-dev \
libxerces-c-dev qt5-default


 
 
                -------------------------Geant4-----------------------------
                
                
cmake -DCMAKE_INSTALL_PREFIX=../geant4.10.06-install \          %LOCAL INSTALL%
-DGEANT4_INSTALL_DATADIR=../data \                      %FILES LOCATION GEANT4%             
-DGEANT4_USE_GDML=ON \
-DGEANT4_USE_QT=ON \
-DGEANT4_USE_RAYTRACER_X11=ON \
-DGEANT4_USE_OPENGL_X11=ON \
-DGEANT4_BUILD_MULTITHREADEAD=ON \
.. 



               -------------------------------------------------------------
