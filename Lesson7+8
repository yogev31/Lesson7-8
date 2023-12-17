public class ArithmeticProgression {
    private int firstMember;
    private int difference;
    public ArithmeticProgression(int fM, int diff)
    {
        firstMember = fM;
        difference = diff;
    }

    public int getFirstMember() {
        return firstMember;
    }

    public void setFirstMember(int firstMember) {
        this.firstMember = firstMember;
    }

    public int getDifference() {
        return difference;
    }

    public void setDifference(int difference) {
        this.difference = difference;
    }
    public void printGeneralSeries()
    {
        System.out.println("An = " + getFirstMember() + " + " + "(n-1)" + getDifference());
    }
    public int memberCalculation(int n)
    {
        return (getFirstMember()+(n-1)*getDifference());
    }
    static boolean isInteger(double N)
    {

        int X = (int)N;
        double temp2 = N - X;

        return !(temp2 > 0);
    }
    public float calculateN(int an)
    {
        float num = an- (float) getFirstMember() /getDifference()+1;
        if(isInteger(num))
        {
            return num;
        }
        else
        {
            return 0;
        }
    }

    public ArithmeticProgression(ArithmeticProgression other)
    {
        this.firstMember = other.firstMember;
        this.difference = other.difference;
    }
    public boolean equal(ArithmeticProgression other)
    {
        return this.difference == other.difference && this.firstMember == other.firstMember;
    }
    public boolean smallDiff(int diff)
    {
        return diff<this.difference;
    }

}
