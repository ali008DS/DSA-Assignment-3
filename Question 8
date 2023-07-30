def can_attend_all_meetings(intervals):
    # Sort the intervals based on the start time
    intervals.sort(key=lambda x: x[0])

    # Check for overlapping intervals
    for i in range(1, len(intervals)):
        if intervals[i][0] < intervals[i - 1][1]:
            return False

    return True
intervals = [[0, 30], [5, 10], [15, 20]]
print(can_attend_all_meetings(intervals))
False
