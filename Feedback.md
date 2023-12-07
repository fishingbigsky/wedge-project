## Feedback 

Nice work on this project, you can consider it complete. I'm going to read your files in order and give you feedback
as I move through them. 

### Task 2

* Nice job on this task.
* I'm surprised that 80 owners was enough to get to 250 GB. You must have gotten a pretty big owner in there. 

### Task 3

```
for i in tqdm(range(int(9e6))):
    pass
```

This line counts to 9,000,000. It _really_ doesn't deserve to be in your final submission. You have cell with `pip install tqdm`, which fits the
same kind of feedback. The best practice is to create a requirements.txt file for a project, 
rather than having your pip install calls in your cells. ChatGPT is pretty good about explaining the concept.

Otherwise this task looks quite good. 


