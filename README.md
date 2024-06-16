# DAY-4
Non -Overlapping Intervals

Problem Statement
Given an array of intervals intervals where intervals[i] = [starti, endi], return the minimum number of intervals you need to remove to make the rest of the intervals non-overlapping.

Solution Approach

I have made vector pair placing end times first followed by start times.Sorted the end times ,so that if its a non-overlapping interval its start time would be greater than previous interval end time.
