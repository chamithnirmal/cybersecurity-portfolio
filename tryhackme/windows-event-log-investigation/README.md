# 🪟 Windows Event Log Investigation

## 📌 Objective

The objective of this project is to learn how Windows Security Event Logs can be used to investigate authentication activity.

## 🛠️ Tools Used

* Windows 10/11
* Windows Event Viewer

## 🔎 Events Investigated

### Event ID 4624

**Description:** Successful account logon.

I investigated a Windows Security event with Event ID 4624 to understand how successful authentication activity is recorded.

### Event ID 4625

**Description:** Failed account logon.

I investigated a Windows Security event with Event ID 4625 to understand how failed authentication attempts are recorded.

## 🔍 Investigation Process

1. Opened Windows Event Viewer.
2. Navigated to Windows Logs → Security.
3. Used the "Filter Current Log" function.
4. Filtered for Event ID 4624.
5. Investigated a successful logon event.
6. Filtered for Event ID 4625.
7. Investigated a failed logon event.
8. Reviewed the available authentication information.

## 📊 Observations

### Event ID 4624

I observed a successful authentication event and examined the available information, including the event time and logon details.

### Event ID 4625

I observed a failed authentication event and examined the available information, including the failure reason and logon details.

## 🧠 What I Learned

Through this investigation, I learned how Windows records authentication activity in the Security Event Log.

I also learned that Event ID 4624 can indicate a successful logon, while Event ID 4625 can indicate a failed logon.

These events can be useful to security analysts when investigating suspicious authentication activity.

## 🔐 Security Considerations

Sensitive information such as usernames, computer names, IP addresses, and other personally identifiable information has been removed or hidden from the screenshots included in this project.

## 📸 Evidence

Screenshots of the investigation are included in the `screenshots` directory.

## 🎯 Future Improvements

Future investigations could analyze multiple failed logon attempts, unusual logon types, authentication patterns, and other Windows Security Event IDs.
