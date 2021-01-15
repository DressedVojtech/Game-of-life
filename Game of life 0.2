#include <array>
#include <chrono>
#include <ctime>
#include <iostream>
#include <string>
#include <thread>

struct cell {
    int age;
    int max_age;
};

class Cells {
private:
    cell cells[100][100];

public:
    void set_max_age_cells(int num1, int num2, int max_age)
    {
        cells[num1][num2].max_age = max_age;
    }
    int see_max_age(int num1, int num2)
    {
        return cells[num1][num2].max_age;
    }
    int see_cell_age(int num, int num2)
    {
        return cells[num][num2].age;
    }
    void set_cell_age(int num, int num2, int num3)
    {
        cells[num][num2].age = num3;
    }
};

class Area : public Cells {
private:
    
    int luck; //luck in the area            //
    int size; //size of the area            //
    int general_max_age; //general max age in the area //
    std::string letter_dead = ". "; //how dead cells will look    //

public:
    void reproduction()
    {
        for (int i = 0; i < size; i++) {
            for (int j = 0; j < size; j++) {
                //upper left
                if (see_cell_age(i, j) > 0 && see_cell_age(i - 1, j - 1) > 0) {
                    int random_dup = (rand() % 7) + 1;
                    switch (random_dup) {
                    case 1:
                        set_cell_age(i, j + 1, 1);
                        max_age_random(i, j + 1);
                        break;
                    case 2:
                        set_cell_age(i - 1, j, 1);
                        max_age_random(i - 1, j);
                        break;
                    case 3:
                        set_cell_age(i - 2, j - 1, 1);
                        max_age_random(i - 2, j - 1);
                        break;
                    case 4:
                        set_cell_age(i - 1, j - 2, 1);
                        max_age_random(i - 1, j - 2);
                        break;
                    case 5:
                        set_cell_age(i, j - 1, 1);
                        max_age_random(i, j - 1);
                        break;
                    case 6:
                        set_cell_age(i + 1, j, 1);
                        max_age_random(i + 1, j);
                        break;
                    case 7:
                        break;
                    }
                }
                //upper Right
                else if (see_cell_age(i, j) > 0 && see_cell_age(i - 1, j + 1) > 0) {
                    int random_dup = (rand() % 7) + 1;
                    switch (random_dup) {
                    case 1:
                        set_cell_age(i, j + 1, 1);
                        max_age_random(i, j + 1);
                        break;
                    case 2:
                        set_cell_age(i - 1, j, 1);
                        max_age_random(i - 1, j);
                        break;
                    case 3:
                        set_cell_age(i - 2, j + 1, 1);
                        max_age_random(i - 2, j + 1);
                        break;
                    case 4:
                        set_cell_age(i - 1, j + 2, 1);
                        max_age_random(i - 1, j + 2);
                        break;
                    case 5:
                        set_cell_age(i, j - 1, 1);
                        max_age_random(i, j - 1);
                        break;
                    case 6:
                        set_cell_age(i + 1, j, 1);
                        max_age_random(i + 1, j);
                        break;
                    case 7:
                        break;
                    }
                }
                //right side
                else if (see_cell_age(i, j) > 0 && see_cell_age(i, j + 1) > 0) {
                    int random_dup = (rand() % 7) + 1;
                    switch (random_dup) {
                    case 1:
                        set_cell_age(i, j + 2, 1);
                        max_age_random(i, j + 2);
                        break;
                    case 2:
                        set_cell_age(i + 1, j + 1, 1);
                        max_age_random(i + 1, j + 1);
                        break;
                    case 3:
                        set_cell_age(i + 1, j, 1);
                        max_age_random(i + 1, j);
                        break;
                    case 4:
                        set_cell_age(i, j - 1, 1);
                        max_age_random(i, j - 1);
                        break;
                    case 5:
                        set_cell_age(i - 1, j, 1);
                        max_age_random(i - 1, j);
                        break;
                    case 6:
                        set_cell_age(i - 1, j + 1, 1);
                        max_age_random(i - 1, j + 1);
                        break;
                    case 7:
                        break;
                    }
                }
                //down
                else if (see_cell_age(i, j) > 0 && see_cell_age(i + 1, j) > 0) {
                    int random_dup = (rand() % 7) + 1;
                    switch (random_dup) {
                    case 1:
                        set_cell_age(i, j + 1, 1);
                        max_age_random(i, j + 1);
                        break;
                    case 2:
                        set_cell_age(i - 1, j, 1);
                        max_age_random(i - 1, j);
                        break;
                    case 3:
                        set_cell_age(i, j - 1, 1);
                        max_age_random(i, j - 1);
                        break;
                    case 4:
                        set_cell_age(i + 1, j - 1, 1);
                        max_age_random(i + 1, j - 1);
                        break;
                    case 5:
                        set_cell_age(i + 2, j, 1);
                        max_age_random(i + 2, j);
                        break;
                    case 6:
                        set_cell_age(i + 1, j + 1, 1);
                        max_age_random(i + 1, j + 1);
                        break;
                    case 7:
                        break;
                    }
                }
            }
        }
    }
    void max_age_random(int i, int j)
    {
        int random = (rand() % 15) + 1;
        if (random == 1)
            set_max_age_cells(i, j, (general_max_age - 1));
        else if (random == 2 || random == 3 || random == 4)
            set_max_age_cells(i, j, (general_max_age + 1));
        else
            set_max_age_cells(i, j, general_max_age);
    }
    void set_max_age()
    {
        srand(time(0));
        std::cin >> general_max_age;
        if (general_max_age > 8) {
            std::cout << "Sorry, maximal maximal age is 8\n(otherwise it wouldn't look as good)\n  Do you want to change yor input to 8? (y/n)" << std::endl;
            std::string answer;
            std::cin >> answer;
            if (answer == "y")
                general_max_age = 8;
        }
        for (int i = 0; i < size; i++) {
            for (int j = 0; j < size; j++) {
                max_age_random(i, j);
            }
        }
    }
    void show()
    {
        int something = 0;
        int something2 = 0;
        for (int i = 0; i < size; i++) {
            for (int j = 0; j < size; j++) {
                if (see_cell_age(i, j) == 0) {
                    std::cout << letter_dead;
                    something++;
                } else {
                  std::cout << /*see_cell_age(i, j) <<*/ "# ";
                  something2++;
                }
                if ((j + 1) % size == 0)
                    std::cout << std::endl;
            }
        }
        if (something >= (size* size ) || something2 >= (size* size))
            exit(0);
    }
    void Aging()
    {
        for (int i = 0; i < size; i++) {
            for (int j = 0; j < size; j++) {
                if (see_cell_age(i, j) > 0) {
                    set_cell_age(i, j, (see_cell_age(i, j) + 1));
                }
                if (see_cell_age(i, j) > see_max_age(i, j)) {
                    set_cell_age(i, j, 0);
                }
            }
        }
    }
    void set_random()
    {
        srand(time(0));
        for (int i = 0; i < size; i++) {
            for (int j = 0; j < size; j++) {
                int random1 = (rand() % luck) + 1;
                if (random1 == 1)
                    set_cell_age(i, j, 1);
            }
        }
    }
    void set_size()
    {
        std::cin >> size;
    }
    void set_luck()
    {
        std::cin >> luck;
    }
    int see_luck()
    {
        return luck;
    }
    int see_size()
    {
        return size;
    }
    
};

void sleep(int num)
{
    std::this_thread::sleep_for(std::chrono::seconds(num));
}

int main()
{
Start:
    Cells c;
    Area a;

    std::cout << "input size" << std::endl;
    a.set_size();
    std::cout << "×" << a.see_size() << std::endl
              << std::endl;

    std::cout << "input chance of life" << std::endl
              << "1:";
    a.set_luck();

    std::cout << std::endl
              << "input maximum age" << std::endl;

    a.set_max_age();

    a.set_random();

    while (true) {
        a.show();
        std::cout << std::endl;
        sleep(1);
        a.Aging();
        a.reproduction();
    }
}
