# mlpack-openmp-issue

  You can run the "ResNet.cpp" with armadillo and openmp. 
  The program uses 4 threads and dynamics teams is turned off.

  train.csv - contains 1999 images from the MNIST, it is used by default.
  train_sample.csv - contains 32 images from MNIST.

  resnet_omp_log.rpt - contains the report generated by valgrind memcheck.
  resnet_omp_log_drd.rpt - containes the report generated by valgrind DRD tool. 


