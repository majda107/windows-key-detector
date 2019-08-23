# Global key detector #

### Example usage ###

Create new instance of KeyDetector
`KeyDetector detector = new KeyDetector();`

Hook events
`
detector.KeyDetected += (o, e) =>
	{
		Console.WriteLine(e.Key);
	};
`

Start key detection thread
`detector.Run();`
