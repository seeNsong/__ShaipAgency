# ShaipAgency
샤입에이전트 개인 프로젝트

## 1. 솔루션 뼈대 작성
### Project 생성
- ShaipAgency.Data              : 데이터 서비스  .Net Standard 2.1 (Class Templates)
- ShaipAgency.Models            : 모델          Class Library .Net Standard 2.1
- ShaipAgency.ServerSide        : 이용자화면     ASP.Net Core 3.1 (Blazor Server Side Templates)
- ShaipAgency.ServerSide.Admin  : 관리자화면     ASP.Net Core 3.1 (Blazor Server Side Templates)

## 2. 로그인 기능 추가
### Identity Project 생성
- ShaipAgency.Areas             : 가입,로그인/아웃,정보수정 : ASP.Net Core Web Application
- Staffolded ASP.Net Core Identity 추가
### ShaipAgency.ServerSide 변경
- Nuget 설치 : Microsoft.EntityFrameworkCore.Design
### ShaipAgetcy.Data 변경
- Nuget 설치Microsoft.EntityFrameworkCore.SqlServer
- DB Migration 생성 : Add-Migration InitialCreate
- DB Migration : Update-Database

# 중단 2020.04.22
- LoginDisplay 배치 중 로그인 및 로그인, 회원가입, 회원정보 수정 안됨
- ShaipAgency.Areas 와 ShaipAgency.ServerSide 의 로그인 정보를 공유못하는 것 같음

