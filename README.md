# Project1
Lucence query to fetch data from elasticsearch

## Problem Statement

We have few critical jobs in production, we need to check manually in autosys UI,
due to some code issue, job doesn't fail properly and it will be in running state in autosys UI,
even the fix is applied behavior job is still same, but it need to be verified on daily basis.

## Solution

For this issue, i have written a lucence query, that will fetch the jobs status from elasticsearch
creates a report in mail and sends mail specific intervals of time and end of day report.
