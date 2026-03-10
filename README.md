# Application-level-Queue-program-8

# Queue Program - Bank Customer Service

queue = []

# Enqueue (customers joining the queue)
queue.append("Customer1")
queue.append("Customer2")
queue.append("Customer3")

print("Customers in Queue:", queue)

# Dequeue (serving the first customer)
served = queue.pop(0)
print("Customer Served:", served)

print("Remaining Queue:", queue)



Customers in Queue: ['Customer1', 'Customer2', 'Customer3']
Customer Served: Customer1
Remaining Queue: ['Customer2', 'Customer3']
