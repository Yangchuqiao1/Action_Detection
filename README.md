# Action_Detection
import numpy as np
import cv2 as cv

cap = cv.VideoCapture("E:/opencv_vs/opencv/sources/samples/data/vtest.avi")

feature_params = dict(maxCorners=100,
                      qualityLevel=0.3,
                      minDistance=7,
                      blockSize=7)
