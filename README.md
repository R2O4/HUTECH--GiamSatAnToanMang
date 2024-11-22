# HUTECH--GiamSatAnToanMang


Invoke-WebRequest -Uri https://packages.wazuh.com/4.x/windows/wazuh-agent-4.5.4-1.msi -OutFile ${env:tmp}\wazuh-agent.msi; msiexec.exe /i ${env:tmp}\wazuh-agent.msi /q WAZUH_MANAGER='192.168.24.146' WAZUH_REGISTRATION_SERVER='192.168.24.146' WAZUH_AGENT_GROUP='default' WAZUH_AGENT_NAME='Win10_Agent' 
