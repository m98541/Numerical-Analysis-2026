# Numerical Analysis 2026 

2026년도 수치해석학 1, 2학기 과제 및 파이썬 실습 코드 레포지토리입니다. 
수학적 이론을 단순히 이해하는 것에 그치지 않고, 파이썬(Python)을 활용해 직접 수치 해석 알고리즘을 구현하며 오차율과 수렴성을 분석했습니다.

## Key Topics (Semester 2)
2학기 과정에서는 선형 연립방정식의 반복 해법, 경계값 문제(BVP), 그리고 다변수 비선형 방정식 등을 중점적으로 다루고 구현했습니다.

* **Systems of Linear Equations (선형 연립방정식의 반복 해법)**
  * Jacobi Method, Gauss-Seidel Method
  * *구현 목적:* 고유값(Eigenvalue)과 스펙트럼 반경(Spectral Radius)을 통한 수렴성 증명 및 두 방식의 반복 횟수에 따른 수렴 속도/오차 비교
* **Boundary-Value Problems (경계값 문제, BVP)**
  * Linear Shooting Method (with Euler's Method & RK4)
  * Nonlinear Shooting Method (with Newton's Method)
  * *구현 목적:* 경계값 문제를 초기값 문제(IVP)로 변환하여 근사해를 도출하고, 적용된 적분 방식(Euler vs RK4)에 따른 오차율 및 스텝 사이즈(N)의 영향 분석
* **Nonlinear Systems & FDM (다변수 비선형 방정식 및 유한차분법)**
  * Multivariable Newton's Method (Jacobian Matrix 도출)
  * Finite-Difference Method (FDM) for Nonlinear BVP
  * *구현 목적:* 다변수 함수의 편미분과 야코비 행렬을 이용한 다변수 뉴턴 메서드 구현 및 비선형 시스템의 행렬식 변환 실습

## Repository Structure
```text
Numerical-Analysis-2026
┣ Semester_1
┃ ┣ Assignment_1_Root_Finding
┃ ┣ Assignment_2_Lagrange_Interpolation
┃ ┣ Assignment_3_Cubic_Spline
┃ ┣ Assignment_4_Taylor_Method
┃ ┣ Assignment_5_Predator_Prey_RK4
┃ ┗ Assignment_6_7_SIR_Model
┗ Semester_2
  ┣ Assignment_1_Jacobi_GaussSeidel
  ┣ Assignment_2_Shooting_Method_BVP
  ┣ Assignment_3_Jacobian_FDM
  ┗ Assignment_4_WIP
