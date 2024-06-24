const startUTCDateTime = '2024-06-24T09:29:50Z'
const endUTCDateTime = '2024-06-24T09:31:00Z'

function isBetweenDates(startUTCTime, endUTCTime) {
    const startTime = new Date(startUTCTime).toISOString();
    const endTime = new Date(endUTCTime).toISOString();
    const utcNow = new Date().toISOString();
    return utcNow >= startTime && utcNow <= endTime;
}

isBetweenDates(startUTCDateTime, endUTCDateTime);

// note: toISOString converts time object to UTC time in ISO format
