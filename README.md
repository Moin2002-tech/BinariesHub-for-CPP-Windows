# BinariesHub-for-CPP-Windows
BinariesHub for C++ Windows Your one-stop repository for all AI and Machine Learning binaries compatible with C++ on Windows. Simplify your development workflow with prebuilt, high-performance binaries tailored for seamless integration in your projects. Explore resources for libraries like LibTorch, mlpack, dlib, OpenCV.

# Libtorch 2.6.0 CPU Debug x64-windows
# Link:
https://16sxj-my.sharepoint.com/:u:/g/personal/moinshaikhofficial_16sxj_onmicrosoft_com/EVYy1IhXpD5Kloi4gXu-FWQB_AQbeb-O-yXpTge1q8sKcQ?e=liJ9k8

# Libtorch 2.6.0 CUDA 12.4 Debug x64-windows
# Link:
https://16sxj-my.sharepoint.com/:u:/g/personal/moinshaikhofficial_16sxj_onmicrosoft_com/ETaYFB82ibdFvAUkTuefSPoB-aKY_1CaZGhTHx9rbgHIJA?e=HJwEKd

# Libtorch 2.6.0 CUDA 12.4 Release x64-windows
# Link:
https://16sxj-my.sharepoint.com/:u:/g/personal/moinshaikhofficial_16sxj_onmicrosoft_com/EeUxnTRBM41MhL1qXQQwTqQBoFkDjbVOhYCfgUeSvswRdQ?e=fR8Ye9

# AI development Ready Binaries /* VCPKG *\ Windows
# Link: 
https://16sxj-my.sharepoint.com/:u:/g/personal/moinshaikhofficial_16sxj_onmicrosoft_com/EVyFW6LBtYlGnywsvt8FjvQBbCvNxZnVyCCjP6JKKm6iGw?e=Qg10in

# vcpkg Prebuilt Binaries Integration
Welcome to the vcpkg Prebuilt Binaries Integration repository! This project provides prebuilt vcpkg binaries and demonstrates how to integrate them seamlessly into your projects, similar to how NuGet Package Manager works in Visual Studio Community 2022.

# Getting Started
Prerequisites
To start using the prebuilt binaries, ensure you have the following:
Visual Studio Community 2022 (or any compatible edition).
vcpkg prebuilt binaries downloaded from the provided link.
Basic knowledge of C++ project setup in Visual Studio.

# Integration Instructions
Step 1: Download Prebuilt Binaries
Download the prebuilt binaries from this link.

# Step 2: Set Up vcpkg in Your Project
Open Visual Studio Community 2022 and navigate to your project folder.
Place the vcpkg prebuilt binaries in a suitable location (e.g., a dedicated vcpkg folder in your project directory).
Open the Command Prompt and run:

sh
vcpkg integrate install
This command will set up the integration with Visual Studio.
Integration Instructions Using vcpkg integrate project

# Step 3: Download Prebuilt Binaries
Download the prebuilt binaries from this link.

Extract the binaries into a dedicated folder, such as vcpkg in your project directory.

# Step 4: Enable Project Integration with vcpkg
Open Developer Command Prompt with administrative privileges.

Navigate to the location of the vcpkg executable using the cd command.

Run:

sh
vcpkg integrate project
This command will generate NuGet configuration files that Visual Studio recognizes, enabling seamless integration of vcpkg packages into your project.
configuration code look this! : 
With a project open, go to Tools->NuGet Package Manager->Package Manager Console and paste:
 Install-Package "vcpkg.H.dev.vcpkg" -Source "H:\dev\vcpkg"
 
# Step 5: Integration in Visual Studio
Open your project in Visual Studio Community 2022.

Go to Tools > NuGet Package Manager > Manage NuGet Packages for Solution.
and paste this into console
 Install-Package "vcpkg.H.dev.vcpkg" -Source "H:\dev\vcpkg"

