# Priority Queue using heapq

import heapq

# Create empty priority queue
pq = []

# Insert elements
heapq.heappush(pq, 30)
heapq.heappush(pq, 10)
heapq.heappush(pq, 20)
heapq.heappush(pq, 5)

print("Priority Queue:", pq)

# Remove elements (smallest first)
print("Deleted element:", heapq.heappop(pq))
print("Deleted element:", heapq.heappop(pq))

print("Priority Queue after deletion:", pq)# sanjanadevi-program-5
