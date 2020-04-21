# ShaipAgency
샤입에이전트 개인 프로젝트

## 1. 솔루션 뼈대 작성
### Project 생성
- ShaipAgency.Data              : 데이터 서비스 .net Standard 2.1
- ShaipAgency.Models            : 모델          .net Standard 2.1
- ShaipAgency.ServerSide        : 이용자화면     .Blazor Server Side Templates
- ShaipAgency.ServerSide.Admin  : 관리자화면     .Blazor Server Side Templates

## 2. 로그인 기능 추가
### ShaipAgency.Areas           : 가입,로그인/아웃,정보수정             : Staffolded ASP.Net Core Identity 추가
### ShaipAgency.ServerSide
- Nuget 설치 : Microsoft.EntityFrameworkCore.Design
### ShaipAgetcy.Data
- Nuget 설치Microsoft.EntityFrameworkCore.SqlServer
- DB Migration 생성 : Add-Migration InitialCreate
- DB Migration : Update-Database

