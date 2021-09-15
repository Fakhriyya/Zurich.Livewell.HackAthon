# Zurich.Livewell.HackAthon
Demo Data Repository For Zurich HackAthon

# Contents

2 files are provided for consumption. They are in json format.

Activity.json
Recipes.json

## Activity
    
    Contains 2 types of documents defined by the variable documenttypeid.
    1 = physcial activity data
    2 = sleep data
    
    --------------------------------------------------------------
    Activity Document
    --------------------------------------------------------------

    "offset": "-03:00", -- Time Offsett
    "steps": 5529,      -- Total Steps
    "activity_score": 410,
    "calories": 179, -- Total Calories
    "distance": 3485,
    "exercise_minutes": 29,
    "moderately_active_minutes": 25,
    "vigorously_active_minutes": 4,
    "met": 247, -- Metabolic Equivalent
    "workout_sessions": null,
    "activity_intensity": null,
    "hourly": [ --Workout in hourly intervals
        {
            "distance": 0,
            "vigorously_active_minutes": 0,
            "calories": 0,
            "moderately_active_minutes": 0,
            "time": "2021-09-15T00:00:00",
            "met": 0,
            "steps": 6
        },
        {
            "distance": 17,
            "vigorously_active_minutes": 0,
            "calories": 2,
            "moderately_active_minutes": 0,
            "time": "2021-09-15T07:00:00",
            "met": 2,
            "steps": 41
        },
        {
            "distance": 6,
            "vigorously_active_minutes": 0,
            "calories": 3,
            "moderately_active_minutes": 0,
            "time": "2021-09-15T09:00:00",
            "met": 3,
            "steps": 64
        },
        {
            "distance": 1056,
            "vigorously_active_minutes": 0,
            "calories": 45,
            "moderately_active_minutes": 10,
            "time": "2021-09-15T10:00:00",
            "met": 71,
            "steps": 1485
        },
        {
            "distance": 29,
            "vigorously_active_minutes": 0,
            "calories": 2,
            "moderately_active_minutes": 0,
            "time": "2021-09-15T11:00:00",
            "met": 2,
            "steps": 43
        },
        {
            "distance": 188,
            "vigorously_active_minutes": 0,
            "calories": 17,
            "moderately_active_minutes": 0,
            "time": "2021-09-15T12:00:00",
            "met": 17,
            "steps": 334
        },
        {
            "distance": 91,
            "vigorously_active_minutes": 0,
            "calories": 8,
            "moderately_active_minutes": 0,
            "time": "2021-09-15T13:00:00",
            "met": 8,
            "steps": 157
        },
        {
            "distance": 375,
            "vigorously_active_minutes": 0,
            "calories": 31,
            "moderately_active_minutes": 0,
            "time": "2021-09-15T14:00:00",
            "met": 30,
            "steps": 606
        },
        {
            "distance": 45,
            "vigorously_active_minutes": 0,
            "calories": 4,
            "moderately_active_minutes": 0,
            "time": "2021-09-15T17:00:00",
            "met": 3,
            "steps": 68
        },
        {
            "distance": 255,
            "vigorously_active_minutes": 0,
            "calories": 12,
            "moderately_active_minutes": 2,
            "time": "2021-09-15T18:00:00",
            "met": 18,
            "steps": 382
        },
        {
            "distance": 425,
            "vigorously_active_minutes": 0,
            "calories": 19,
            "moderately_active_minutes": 4,
            "time": "2021-09-15T19:00:00",
            "met": 30,
            "steps": 617
        },
        {
            "distance": 999,
            "vigorously_active_minutes": 4,
            "calories": 36,
            "moderately_active_minutes": 4,
            "time": "2021-09-15T20:00:00",
            "met": 63,
            "steps": 1303
        }
    ],    
    "memberidguid": "e838b2b8-1082-457c-bfe8-574c6911f4c3",    
    "documenttypeid": 1,
    "dateinserted": 1631700000000, --Epoch Datetime
    "activitydate": 1631674800000, --Epoch Datetime   

    --------------------------------------------------------------
    Sleep Document
    --------------------------------------------------------------
    
    "offset": "+3:00",
    "sleep_duration_today": 400,
    "memberidguid": "e838b2b8-1082-457c-bfe8-574c6911f4c3",    
    "documenttypeid": 2,
    "dateinserted": 1630808154000, --Epoch Datetime
    "activitydate": 1630808154000, --Epoch Datetime   