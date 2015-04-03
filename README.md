# ListHouse
Class List House
 @author CHANUKA-HANSANI
 
class ListHouse implements Listable{

    public ListHouse(int lotNumber, String firstName, String lastName, int price, int squareFeet, int bedRooms) {
        this.lotNumber = lotNumber;
        this.firstName = firstName;
        this.lastName = lastName;
        this.price = price;
        this.squareFeet = squareFeet;
        this.bedRooms = bedRooms;
    }

    private int lotNumber;
    private String firstName;
    private String lastName;
    private int price;
    private int squareFeet;
    private int bedRooms;

    /**
     * @return the lotNumber
     */
    public int getLotNumber() {
        return lotNumber;
    }

    /**
     * @param lotNumber the lotNumber to set
     */
    public void setLotNumber(int lotNumber) {
        this.lotNumber = lotNumber;
    }

    /**
     * @return the firstName
     */
    public String getFirstName() {
        return firstName;
    }

    /**
     * @param firstName the firstName to set
     */
    public void setFirstName(String firstName) {
        this.firstName = firstName;
    }

    /**
     * @return the lastName
     */
    public String getLastName() {
        return lastName;
    }

    /**
     * @param lastName the lastName to set
     */
    public void setLastName(String lastName) {
        this.lastName = lastName;
    }

    /**
     * @return the price
     */
    public int getPrice() {
        return price;
    }

    /**
     * @param price the price to set
     */
    public void setPrice(int price) {
        this.price = price;
    }

    /**
     * @return the squareFeet
     */
    public int getSquareFeet() {
        return squareFeet;
    }

    /**
     * @param squareFeet the squareFeet to set
     */
    public void setSquareFeet(int squareFeet) {
        this.squareFeet = squareFeet;
    }

    /**
     * @return the bedRooms
     */
    public int getBedRooms() {
        return bedRooms;
    }

    /**
     * @param bedRooms the bedRooms to set
     */
    public void setBedRooms(int bedRooms) {
        this.bedRooms = bedRooms;
    }
}
