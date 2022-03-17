class Calculator
{
	static void Main(String[]args)
	{
		int a = 10;
		int b = 6;
		
		Console.WriteLine("Hasil penmabahan :{0} + {1} = {2}",a,b, Penambahan (a,b));
		Console.WriteLine("HasilPengurangan :{0} - {1} = {2}",a,b, Pengurangan (a,b));

		Console.WriteLine("\nTekan sembarang key untuk keluar');
		Console.Readkey();
	}
	Static int penambahan(int a, int b)
	{
		return a + b;
	}
	static int pengurangan(int a, int b)
		return a-b;
	}
}