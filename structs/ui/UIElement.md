# UIElement

```cpp
//sizeof == 38
struct UIElement {
    short x;                     //0
    short y;                     //2
    short width;                 //4
    short height;                //6
    short mainTexture;           //8
    short valueLink;             //10
    short unknown;               //12
    short buttonPressedTexture;  //14
    int textOffset;              //16
    short tooltipLink;           //20
    short tooltipLinkExtra;      //22
    byte imageStyle;             //24
    byte id;                     //25
    //enum where the first 4 bits define which font style to use and last 4 bits define effects (Like pressed etc)
    byte textStyle;              //26
    byte effects;                //27
    short unknown4;              //28
    byte drawParams;             //30
    byte uiGroupId;              //31
    byte unknownData0;           //32
    byte caretPosition;          //33
    short unknownData1;          //34
};

```