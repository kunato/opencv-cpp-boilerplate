### OpenCV installation

```
cmake -D CMAKE_BUILD_TYPE=RELEASE \
            -D CMAKE_INSTALL_PREFIX=~/opencv_cpp_4.1.0 \
            -D INSTALL_C_EXAMPLES=ON \
            -D WITH_TBB=ON \
            -D WITH_V4L=ON \
            -D WITH_QT=OFF \
            -D WITH_EIGEN=ON \
            -D WITH_OPENGL=ON \
            -D OPENCV_EXTRA_MODULES_PATH=../../opencv_contrib/modules \
            -D BUILD_EXAMPLES=ON ..

make -j4
make install
```

```
mkdir build
cmake ..
make
./OpenCVBoilerplate
```
