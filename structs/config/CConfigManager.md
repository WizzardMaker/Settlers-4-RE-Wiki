# CConfigManager

```cpp
typedef CMap<wstring, CConfigVar*> ConfigVarMap;
typedef CList<CConfigSection*> ConfigSectionList;

class CConfigManager{
    ConfigVarMap *definitionsList;
    int field_8;
    ConfigSectionList sectionList;

    virtual CConfigManager* dtor(CConfigManager *lpMem, char a2);
    virtual int             sub_2275E0(CConfigManager *this, int a2);
    virtual char            sub_227350(CConfigManager *this, const char *a2, int a3, int a4);
    virtual int             RetrieveIntConfig(CConfigManager *this, const char *section, const char *name, int default);
    virtual int*            RetrieveFloatConfig(CConfigManager *this, const char *section, const char *name, float default);
    virtual int             RetrieveStringConfig(CConfigManager *this, wstring *out, const char *section, const char *name, wstring *default);
    virtual int             sub_227600(CConfigManager *this, const char *a2, const char *a3);
    virtual void            sub_228A40(CConfigManager *this, int a2, int a3);
    virtual int             FindDefinition(CConfigManager *this, wstring *a2);
    virtual bool            sub_2296E0(CConfigManager *this, const char *a2, int a3);
    virtual int             sub_2297C0(CConfigManager *this, const char *a2);
    virtual bool            sub_229890(CConfigManager *this, const char *a2, int a3);
    virtual int*            ChangeConfig(CConfigManager *this, const char *a2, const char *a3, int a4);
    virtual int             sub_228EA0(CConfigManager *this, const char *a2, const char *a3, int a4);
    virtual int*            sub_2291C0(CConfigManager *this, int a2, int a3, float a4);
    virtual int             sub_229530(CConfigManager *this, int a2, const char *a3, const char *a4, int a5);
    virtual bool            sub_227530(CConfigManager *this, wchar_t *a1, int a2);
};
```

!!! info
    See [CMap, CList](../../generic/)
