\# Tomcat MCP (Model Context Protocol Server)



A local \*\*Tomcat management MCP server\*\* for \*\*Kiro IDE\*\* that enables AI-assisted

operations such as:



\- Start / stop Tomcat

\- Diagnose startup failures

\- Deploy and rollback WAR files

\- Read and analyze logs

\- Take thread dumps and heap dumps

\- Analyze GC logs

\- Detect Windows service installations



This MCP runs \*\*locally\*\* and never exposes Tomcat over the network.



---



\## 🚀 One-Click Install (Kiro IDE)



> Make sure you have cloned this repository and installed dependencies first.



\[!\[Add to Kiro](https://kiro.dev/images/add-to-kiro.svg)](REPLACE\_WITH\_INSTALL\_LINK)



---



\## 📦 Requirements



\- \*\*Node.js 18+\*\*

\- \*\*Java JDK\*\* (required for `jcmd`, thread dumps, heap dumps)

\- Apache Tomcat (9 / 10 / 10.1 tested)

\- Windows (Linux support planned)



Check:

```bat

node -v

java -version

jcmd -h



