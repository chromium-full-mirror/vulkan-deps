# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '7881226269b1596feb604515743f528f02041375',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'be41e15215d041afa377b6a1176c5c8258116fbb',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'babee77020ff82b571d723ce2c0262e2ec0ee3f1',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'a1eace9772ea3b5f727359db14305baeaf16a7d7',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '0777a3ad88bad5f4b11cfd509458bbc0ddadc773',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '2e60d7384711e20d0ad2357a0be87438f37776ac',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'f5ba3301bdd000d925b4bf277a18ac0fa69c1fd2',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'b4e9ebbfc779cba85f1efbe2f69fdfc5744ed5e5',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '1bcb18ebfbc5f05b38b7f47fa31b438e28f751b0',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
