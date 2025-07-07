api.call("Get", {
    "typeName": "WorkHoliday",
    "resultsLimit": 2
}, function(result) {
    console.log("Done: ", result[1]["holidayGroup"]);
}, function(e) {
    console.error("Failed:", e);
});

const myHolidayGroup=[{"groupId":"1"}];

api.call("Add", {"typeName":"WorkHoliday", "entity":{"date":"2025-09-01T00:00:00.000Z", "holidayGroup":myHolidayGroup[0], "name":"Labor Day"}});
api.call("Add", {"typeName":"WorkHoliday", "entity":{"date":"2025-10-13T00:00:00.000Z", "holidayGroup":myHolidayGroup[0], "name":"Columbus Day"}});
api.call("Add", {"typeName":"WorkHoliday", "entity":{"date":"2025-11-11T00:00:00.000Z", "holidayGroup":myHolidayGroup[0], "name":"Veterans Day"}});
api.call("Add", {"typeName":"WorkHoliday", "entity":{"date":"2025-11-27T00:00:00.000Z", "holidayGroup":myHolidayGroup[0], "name":"Thanksgiving Day"}});
api.call("Add", {"typeName":"WorkHoliday", "entity":{"date":"2025-12-25T00:00:00.000Z", "holidayGroup":myHolidayGroup[0], "name":"Christmas Day"}});
