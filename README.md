# First-Repo
## I'm SUDARSHAN MAHATO

#include <stdio.h>

int getLength(void) {
    int length;
    printf("Enter value: ");
    scanf("%d", &length);
    return length;
}

int getWidth(void) {
    int width;
    printf("Enter rectangle width: ");
    scanf("%d", &width);
    return width;
}

int RectangleArea(int length, int width) {
    int area = length * width;
    printf("The area of the rectangle is %d\n", area);
    return area;
}







int main(void) {
    int length = getLength();
    int width = getWidth();
    RectangleArea(length, width);
    int a =getLength();
    printf("%d",a);
    return 0;
}
