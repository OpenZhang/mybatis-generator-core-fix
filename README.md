# mybatis-generator-core-fix
# 使用 mybatis-generator 1.3.2 自动生成mybatis 结构源码带中文注释；
# 通过lifangyu/mybatis-generator-auto-tools工程使用此工程编译的jar包mybatis-generator-core-1.3.2-fix.jar(是通过工程mybatis-generator-core-fix编译的jar)可以自动生成以下特定样式的中文注释
mybatis generator 生成数据库备注为注释 修整部分代码的样式

本工程为maven项目，可以直接打包使用

生成后的样式：

package com.imooc.seckill.model;

import java.util.Date;

/**
 * 秒杀
 * TbSeckill
 * 数据库表：tb_seckill
 */
public class TbSeckill {

    /**
     * 商品库存id
     * 表字段 : tb_seckill.id
     */
    private Long id;

    /**
     * 商品名称
     * 表字段 : tb_seckill.name
     */
    private String name;



    /**
     * 获取 商品库存id 字段:tb_seckill.id
     *
     * @return tb_seckill.id, 商品库存id
     */
    public Long getId() {
        return id;
    }

    /**
     * 设置 商品库存id 字段:tb_seckill.id
     *
     * @param id the value for tb_seckill.id, 商品库存id
     */
    public void setId(Long id) {
        this.id = id;
    }

    /**
     * 获取 商品名称 字段:tb_seckill.name
     *
     * @return tb_seckill.name, 商品名称
     */
    public String getName() {
        return name;
    }

    /**
     * 设置 商品名称 字段:tb_seckill.name
     *
     * @param name the value for tb_seckill.name, 商品名称
     */
    public void setName(String name) {
        this.name = name == null ? null : name.trim();
    }

}
