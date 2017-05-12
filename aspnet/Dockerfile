FROM microsoft/aspnetcore
WORKDIR /webapp
COPY /webapp/publish /webapp
RUN ls -la /webapp/*
ENTRYPOINT [ "dotnet", "webapp.dll"]