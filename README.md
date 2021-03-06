# CSharpPathTracer

A basic [path tracing](https://en.wikipedia.org/wiki/Path_tracing) implementation written in C#.

## Build & Run

Open the solution in Visual Studio 2017, then build and run.

Or build and run with .NET Core:

```plain
cd CSharpPathTracer
dotnet run
```

Then the rendered image is saved to `D:\\xxx.png`.

## Result

Environment: Win10, i7 8700

Sample: 16, time used: 2.17s:  
![](Images/16_2.17.png)

Sample: 64, time used: 8.64s:  
![](Images/64_8.64.png)

Sample: 256, time used: 34.18s:  
![](Images/256_34.18.png)

Sample: 1024, time used: 133.87s:  
![](Images/1024_133.87.png)

Sample: 4096, time used: 537.05s:  
![](Images/4096_537.05.png)

Unity Scene, used for reference:

![](Images/unity.png)

## Article

(In Chinese) https://zwcloud.net/#blog/98
