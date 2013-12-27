# Changelog

## 0.3.1
  Bug fixes.

## 0.3.0
  Work with new Isolates API.

## 0.2.2
  Minor bug fix.

## 0.2.1
  Bug fixes.

## 0.2.0
	Major rewrite:
	* Isolates now may handle more than one Task at the time.
	* Creation of the WorkerIsolate to abstract comunication with isolates.
	* 'execute' method from Worker renamed to 'handle'.
	* Workers and WorkerIsolates may be closed.
	* Errors are now handled properly.