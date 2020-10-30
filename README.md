# Switch-case
#include <stdio.h>
int main ()
{
    int choice;
    printf("Pick an item:\n1.Pizza\n2.Momos\n3.Kati Roll\n4.French Fries\n5.Burger\n");
    scanf ("%d", &choice);
    switch (choice)
        {
            case 1:
              printf ("Food item-Pizza\nPrice- Rs 179");
              break;
            case 2:
              printf ("Food item-Momos\nPrice- Rs 50");
              break;
            case 3:
              printf ("Food item-Kati Roll\nPrice- Rs 55");
              break;
            case 4:
              printf ("Food item-French Fries\nPrice- Rs 99");
              break;
            case 5:
              printf ("Food item-Burger\nPrice- Rs 129");
              break;
            default:
              printf("Invalid choice");
        }
}
