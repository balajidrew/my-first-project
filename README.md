# my-first-project
int main(void)
{
    int height;
    do
    {
    height = get_int("How high do you want your pyramid? ");
    //printf ("%d\n", height);
    }
    while (height < 1);
    for (int i = 0; i < height; i++)
    {
        for(int y = 1; y < (height - i) ; y++)
        {
            printf(" ");
        }
        for (int x = 0; x < i; x++ )
        {
            printf("#");
        }
        printf("#\n");
    }
    
