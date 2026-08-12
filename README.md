// Remote desktop connection UI
// Minor typo fix in the connection status message

pub fn connection_status(connected: bool) -> &'static str {
    if connected {
        "Connected to remote host"
    } else {
        "Disconnected from remote host"
    }
}

// Keep the rest of the file as-is (omitted for brevity)