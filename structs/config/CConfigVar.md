# CConfigVar

# Definitions

## Base classes

```cpp
class CConfigVar {
    // Probably some type informatione (e.g. static, dynamic, float, int, string, etc.)
    // These are defined as individual chars, but the compiler has optimized their assignments to a single DWORD, so beware
    char field_4;
    char field_5;
    char field_6;
    char field_7;

    virtual int __cdecl ConfigGet0();
    virtual double __cdecl ConfigGet0_0();
    virtual DWORD* __stdcall sub_2E320(DWORD* a1);
    virtual int __cdecl sub_2E360();
    virtual int __cdecl sub_2E370();
    virtual void __stdcall nullsub_508(int a1);
    virtual void __stdcall nullsub_509(int a1);
    virtual void __stdcall nullsub_510(int a1);
    virtual void __stdcall nullsub_511(int a1);
    virtual DWORD* DestroyConfigVar(char a2);
};

class CDynamicConfigVar : public CConfigVar {

    virtual int __cdecl ConfigGet0();
    virtual double __cdecl ConfigGet0_0();
    virtual DWORD* __stdcall sub_2E320(DWORD* a1);
    virtual int __cdecl sub_2E360();
    virtual int __cdecl sub_2E370();
    virtual void __stdcall nullsub_508(int a1);
    virtual void __stdcall nullsub_509(int a1);
    virtual void __stdcall nullsub_510(int a1);
    virtual void __stdcall nullsub_511(int a1);
    virtual _DWORD* DestroyConfigVar(char a2);
};
```

## Type classes

```cpp

class CConfigVarFloat : public CDynamicConfigVar {
    float value;

    virtual int __cdecl ConfigGet0();
    virtual double __cdecl ConfigGet0_0();
    virtual DWORD* __stdcall sub_2E320(DWORD* a1);
    virtual int __cdecl sub_2E360();
    virtual int __cdecl sub_2E370();
    virtual void __stdcall nullsub_508(int a1);
    virtual void __stdcall nullsub_509(int a1);
    virtual void __stdcall nullsub_510(int a1);
    virtual void __stdcall nullsub_511(int a1);
    virtual _DWORD* DestroyConfigVar(char a2);
};

class CConfigVarInt : public CDynamicConfigVar {
    int value;

    virtual int __cdecl ConfigGet0();
    virtual double __cdecl ConfigGet0_0();
    virtual DWORD* __stdcall sub_2E320(DWORD* a1);
    virtual int __cdecl sub_2E360();
    virtual int __cdecl sub_2E370();
    virtual void __stdcall nullsub_508(int a1);
    virtual void __stdcall nullsub_509(int a1);
    virtual void __stdcall nullsub_510(int a1);
    virtual void __stdcall nullsub_511(int a1);
    virtual _DWORD* DestroyConfigVar(char a2);
};

class CConfigVarString : public CDynamicConfigVar {
    wstring value;

    virtual int __cdecl ConfigGet0();
    virtual double __cdecl ConfigGet0_0();
    virtual DWORD* __stdcall sub_2E320(DWORD* a1);
    virtual int __cdecl sub_2E360();
    virtual int __cdecl sub_2E370();
    virtual void __stdcall nullsub_508(int a1);
    virtual void __stdcall nullsub_509(int a1);
    virtual void __stdcall nullsub_510(int a1);
    virtual void __stdcall nullsub_511(int a1);
    virtual _DWORD* DestroyConfigVar(char a2);
};

```

